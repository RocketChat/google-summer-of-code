# Google Summer of Code 2025

## [![Google Summer of Code 2025](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com)

## How to apply

Rocket.Chat is applying to become a participating mentoring open source organization for [Google Summer of Code 2025](https://summerofcode.withgoogle.com/), helping to usher in a new generation of open source contributors and enthusiasts.

For timeline, see [Official Google Summer of Code 2025](https://developers.google.com/open-source/gsoc/timeline) Timeline for more details.

Almost anyone in the world [over 18 years of age](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) who loves coding and wants to explore the incredible world of open source can join us as a GSoC 2025 contributor.

Most exciting news for the 2025 season is a new [focus on ML/AI plus security projects, and the continued support for a small project type with a 90 hours duration](https://opensource.googleblog.com/2023/11/google-summer-of-code-2025-celebrating-20th-year.html); allowing participation from those who can only  devote part of their summer to exploring open source.

For details and rules of Google Summer of Code 2025, please see the [GSoC 2025 Official Website](https://summerofcode.withgoogle.com/). For timeline, see [Official Google Summer of Code 2025 Timeline](https://developers.google.com/open-source/gsoc/timeline) for more details.

### **Contacting Rocket.Chat**

For general information, please visit our 24 x 7 community channel for Google Summer of Code 2025 : [https://open.rocket.chat/channel/gsoc2025](https://open.rocket.chat/channel/gsoc2025)

Join our [Google Summer of Code 2025 Team ](https://open.rocket.chat/channel/gsoc2025) today, introduce yourself to the friendly community, and interact with over **110 like-minded** contributors/mentors (as of January 27, 2025)  and meet the team in the [20+ team channels](https://open.rocket.chat/channel/gsoc2025/team-channels).

If you have ideas and proposals that are not on our idea list, or if a mentor is not available, you can also email to:

gsoc+2025@rocket.chat

But better yet, you can post your idea in the [New GSoC 2025 Ideas looking for mentors](https://open.rocket.chat/channel/New-GSoC-2025-Ideas-looking-for-mentors) channel and possibly getting some immediate community feedback or support for your idea.

Interested contributors are also encouraged to interact directly with our team and community on the team channels:

[https://open.rocket.chat/channel/gsoc2025/team-channels](https://open.rocket.chat/channel/gsoc2025/team-channels)

As well as on GitHub:

[https://github.com/RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)

Those who prefers forums can post messages on our GSoC forum channel (although as the leading open source team chat project we prefer you use Rocket.Chat channels above to reach us instantly).

-----

### **Latest update**

As of January 27th 2025  checkout our [GSoC 2025  Contributors Leaderboard](https://gsoc.rocket.chat/), to see the amazing contributions by our GSoC 2025 community: we already have over 100 contributors and mentors ready to join us for this season, active in our [team channels](https://open.rocket.chat/channel/gsoc2025/team-channels).

## 📂 Project Ideas

> This is an early draft of the GSoC 2025 project ideas list for Rocket.Chat,  the projects are expected to go through constant rapid changes during the application period - as mentors and potential contributors discuss and evolve the project descriptions.

### 💡 An Interesting Placeholder for AI/ML project 

👥 **Mentor(s):**    Mentor 1,  Mentor 2 

💬 **Description:**

A prompt editor is the quintessential development tool for any  AI/ML prompt engineer.   With ever-increasing number of Rocket.Chat users experimenting and developing with open source LLMs, it is important to have a great prompt editor at their disposal.  This project includes the creation of a fully featured prompt editor as a Rocket.Chat app.   This editor should enable free conversation, by any designated/configured Rocket.Chat user, to chat with any open source LLMs (Mistral,  Llama 2,  Phi, and so on), and the ability to save (and manage - delete etc)  all conversation history.   It should also enable a Rocket.Chat users to "share" the prompt(s) to external applications.   Initial implementation should be for the RC Web App (and Electron).  

💪 **Desired Skills:**  Rocket.Chat Apps development.  LLM prompt editor dev experience.

🎯 **Goals/Deliverables:** Rocket.Chat App empowering users to converse freely with open source LLMs and save the conversations.  The app must allow management of these prompts by the user, including deletion, renaming, and sharing of the prompt content via the clipboard or into the chat stream as a message. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡  An interesting placeholder for a UI enhancement project 

👥 **Mentor(s):** Mentor 1 and Mentor 2

💬 **Description:**
Most Rocket.Chat developers uses VSCode when studying our massive production code base, and when writing new code. VSCode is the best environment for conducting interactive tutorial and code walkthroughs. The CodeTour extension available in VSCode can be used to create such walkthrough and tutorials. This project involves the development of a set of guided tutorials using CodeTour that will help new developers to understand how to perform multiple actions. In 2025, we want to extend these tours to include graphical diagrams and flow charts.  

Paths to be documented and graphically enhanced for 2025 include these areas:

* How a message is sent
* How to create an endpoint
* How to add a new service
* How to create a DB model
* How to use DB models
* How services interact between them
* How to build a lib
* How to navigate monorepo (where is everything, how's imported, etc)

We welcome any additional ideas you may have.

💪 **Desired Skills:** NodeJS, MongoDB

🎯 **Goals/Deliverables:** A set of guided tours from the topics described above

⏳ **Project Duration:** 90 hours. (Small)

📈 **Difficulty:** Easy

-----

### 💡 A placeholder for a geat security project 

👥 **Mentor(s):** Mentor 1

💬 **Description:**
A Rocket.Chat app that collects news from top websites like TechCrunch, etc and sends its summary with a link to full content. The technical challenge would be to write different logic to collect news from different sources -> since some has API, some has RSS feed. These sources should be categorized and presented in a "newspaper" or "news feed" format.  News sources and categories should be completely configurable.

💪 **Desired Skills:**
Rocket.Chat App development. 

🎯 **Goals/Deliverables:**
A Rocket.Chat App that can presents users with daily news feed gathered from all over the Internet. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Embedded Chat 2025

👥 **Mentor(s):** Mentor 1

💬 **Description:**
Improvement to the EmbeddedChat project this year includes:
- Creation of a Rocket.Chat App to remotely configure the associated EmbeddedChat instance(s).
- Security improvements for authentication (one such is providing endpoints using the created EmbeddedChat app for RocketChat to support cookie-based authentication instead of storing the token in localStorage).
- Improving the UI library by making it completely headless and adding different pre-built templates).
Bonus: improvements in UI kit rendering inside EmbeddedChat

💪 **Desired Skills:**
Rocket.Chat App development

🎯 **Goals/Deliverables:**
Improved EmbeddedChat that can be configured on the associated Rocket.Chat instance and major security update which requires to completely shift from localStorage to browser cookies. Clean UI for EmbeddedChat and provide users with some pre-built templates so that they can easily get started with EmbeddedChat.

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy/Intermediate


-----

### 💡AI Query Bot: a configurable Retrieval Augmented Generation pipleline executor 
👥 **Mentor(s):** Mentor 1

💬 **Description:**
Create a Rocket.Chat app that answers queries by executing a configurable RAG pipeline.   The RAG pipeline should be configurable via the App's setting - controlling aspects such a embedding/tokenizer engine,  vector database search algorithms, re-ranking strategy,  open source LLM used for generation (Mistral, Llama,  Phi and so on); as well as any prompt used in the pipeline.  The code should have at least two concrete config/examples within two non-trivial problem domains  (feel free to use available public open source data collections).

💪 **Desired Skills:**  Rocket.Chat App development. LLM prompt design/engineering.  RAG pipeline design and development.

🎯 **Goals/Deliverables:** A flexible AI query bot for any problem domain that operates based on a pre-configured RAG pipeline.

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy/Intermediate

-----
