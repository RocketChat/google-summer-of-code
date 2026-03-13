## Running Your Own Rocket.Chat Instance on the Cloud

If you want to experiment with Rocket.Chat with friends or family, one of the easiest ways is to deploy your own instance on a cloud provider.

### Using DigitalOcean

DigitalOcean is a popular option for quick deployments. Students can receive **up to $200 in free credits** for 1 year through the [GitHub Student Developer Pack](https://www.digitalocean.com/github-students), which makes it a great environment for experimenting with infrastructure and hosting your own Rocket.Chat server.

With these credits, you can spin up a VPS, deploy Rocket.Chat, and explore the platform without any initial cost.

### Basic Deployment Steps

1. Create a VPS (Droplet) on DigitalOcean
2. Install the Rocket.Chat server

   **Using Docker**
   1. Install Docker and add user to the docker group on the VPS
   ```sh
   curl -L https://get.docker.com | sh
   sudo usermod -aG docker $USER
   ``` 

   2. First, start an instance of mongo and initiate replicaSet:

   ```sh
   docker run -d --name mongo -p 27017:27017 mongo:7.0 --replSet rs0 --oplogSize 128
   ```

   3. Initialize the replica set

   ```sh
   docker exec -it mongodb mongosh --eval "rs.initiate()"
   ```

   4. Run Rocket.Chat (Latest)

   ```sh
   docker run -d \
   --name rocketchat \
   -p 3000:3000 \
   --link mongodb \
   -e MONGO_URL=mongodb://mongodb:27017/rocketchat \
   -e MONGO_OPLOG_URL=mongodb://mongodb:27017/local \
   -e ROOT_URL=http://localhost:3000 \
   rocket.chat:latest
   ```

   **Using Docker Compose**
   - You can follow this official [documentation](https://docs.rocket.chat/v1/docs/deploy-with-docker-docker-compose#step-1-install-docker-docker-compose-and-git) by Rocket.Chat

3. Start the server and complete the configuration

Once the setup is complete, you will have your own hosted Rocket.Chat instance where you can chat, test integrations, and experiment with the platform.

### Why This Is Useful

Running your own instance allows you to:

- Explore Rocket.Chat's deployment architecture
- Experiment with integrations and configurations
- Learn about DevOps practices such as containerized deployment
- Create a private chat server for friends or family

If you've deployed Rocket.Chat on DigitalOcean or other cloud platforms, feel free to share your experience with the community!
