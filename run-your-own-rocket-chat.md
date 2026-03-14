# 🚀 Want to run your own Rocket.Chat server and chat with friends?

Ever wondered what it’s like to run your **own secured chat platform** instead of using someone else’s?  
Good news 🌟, it’s actually much easier than you might think 😄

💡 **DigitalOcean offers up to $200 in free credits** through the **GitHub Student Developer Pack 🎓**.

That means you can experiment with cloud infrastructure, deploy Rocket.Chat, and run your own chat server **without paying anything until the credits run out** 💻🚀

So what does it take?

It’s actually as simple as it sounds:

- Create a VPS
- Install the Rocket.Chat server via Docker (or use Snap if you're on Ubuntu)
- Run the server and configure it

And voilà ✨ you just created your own hosted Rocket.Chat platform where you can chat and experiment with friends or family.

If you'd like to try this yourself, here’s a quick guide to get started.

## 🛠 Step-by-Step Deployment Guide

### 1️⃣ Create a VPS

Create a **Droplet (VPS)** on DigitalOcean.

Students can receive **up to $200 in free credits for 1 year** through the GitHub Student Developer Pack:

https://www.digitalocean.com/github-students


### 2️⃣ Install Rocket.Chat

### Option 1 — Using Docker 🐳

Install Docker and add your user to the docker group:

```sh
curl -L https://get.docker.com | sh
sudo usermod -aG docker $USER
```

Start a MongoDB instance and enable replica set
```sh
docker run -d --name mongodb -p 27017:27017 mongo:7.0 --replSet rs0 --oplogSize 128
```

Initialize the replica set:
```sh
docker exec -it mongodb mongosh --eval "rs.initiate()"
```

Run Rocket.Chat 🚀
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

### Option 2 — Using Docker Compose 🐳
If you prefer Docker Compose, you can follow the official Rocket.Chat guide:
https://docs.rocket.chat/docs/deploy-with-docker-docker-compose

### 3️⃣ Launch your server 🎉
Once everything is running, open your browser and visit:
```
http://YOUR_SERVER_IP:3000
```
You can also attach a good domain name as well to this server to make it look interactive

Complete the setup wizard and your Rocket.Chat instance will be ready to use.

Happy Deploying 🚀