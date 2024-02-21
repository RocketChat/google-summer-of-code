# Google Summer of Code 2024

## [![Google Summer of Code 2024](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com)

## How to apply

Rocket.Chat has applied to become a participating mentoring open source organization for [Google Summer of Code 2024](https://summerofcode.withgoogle.com/), helping to usher in a new generation of open source contributors and enthusiasts.

For timeline, see [Official Google Summer of Code 2024](https://developers.google.com/open-source/gsoc/timeline) Timeline for more details.

Almost anyone in the world [over 18 years of age](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) who loves coding and wants to explore the incredible world of open source can join us as a GSoC 2024 contributor.

Most exciting news for the 2024 season is a new [focus on ML/AI projects, and the introduction of a small project type with a 90 hours duration](https://opensource.googleblog.com/2023/11/google-summer-of-code-2024-celebrating-20th-year.html); allowing participation from those who can only  devote part of their summer to exploring open source.

For details and rules of Google Summer of Code 2024, please see the [GSoC 2024 Official Website](https://summerofcode.withgoogle.com/). For timeline, see [Official Google Summer of Code 2024 Timeline](https://developers.google.com/open-source/gsoc/timeline) for more details.

### **Contacting Rocket.Chat**

For general information, please visit our 24 x 7 community channel for Google Summer of Code 2024 : [https://open.rocket.chat/channel/gsoc2024](https://open.rocket.chat/channel/gsoc2024)

Join our [Google Summer of Code 2024 Team ](https://open.rocket.chat/channel/gsoc2024) today, introduce yourself to the friendly community, and interact with over **200 like-minded** contributors/mentors and meet the team in the [ 36 team channels](https://open.rocket.chat/channel/gsoc2024/team-channels).

If you have ideas and proposals that are not on our idea list, or if a mentor is not available, you can also email to:

gsoc+2024@rocket.chat

But better yet, you can post your idea in the [New GSoC 2024 Ideas looking for mentors](https://open.rocket.chat/channel/New-GSoC-2024-Ideas-looking-for-mentors) channel and possibly getting some immediate community feedback or support for your idea.

Interested contributors are also encouraged to interact directly with our team and community on the team channels:

[https://open.rocket.chat/channel/gsoc2024/team-channels](https://open.rocket.chat/channel/gsoc2024/team-channels)

As well as on GitHub:

[https://github.com/RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)

Those who prefers forums can post messages on our GSoC forum channel (although as the leading open source team chat project we prefer you use Rocket.Chat channels above to reach us instantly).

-----

### **Latest update**

Check out our [GSoC 2024 Contributors Leaderboard](https://gsoc.rocket.chat/), to see the amazing contributions by our GSoC 2024 community: **95 new contributors creating 57 Merged PRs, 85 Open PRs, and 171 Issues** as of **February 8, 2024**!  

A group of returning GSoC mentors has help us to put together and launched the second instance of the  ["How to build a Rocket.Chat App hands-on workshop"](https://open.rocket.chat/channel/events-and-meet-ups?msg=uMbtzA7Ke96ScEMu5) on **February 2, 2024**.  The session was filled within 24 hours of announcement.    Thanks goes to the second 15 ethusisastic attendees for providing us with valuable feedback for improvement.    We intend to refine this workshop over the GSoC 2024 season and will be running incrementally improving instances weekly throughout Feb and March.

Check out our [GSoC 2024 Contributors Leaderboard](https://gsoc.rocket.chat/), to see the amazing contributions by our GSoC 2024 community: **63 new contributors creating 42 Merged PRs, 65 Open PRs, and 118 Issues** as of **January 28, 2024**!  

We launch the very first instance of ["How to build a Rocket.Chat App hands-on workshop"](https://open.rocket.chat/channel/events-and-meet-ups?msg=aJ3cvE2umJjzLaF9B) on **January 26th, 2024**.   This workshop is created by a panel of our community mentors and is intended to prepare our contributors for their Google Summer of Code 2024 contributions. The workshop was over subscribed upon announcement.   Thanks to the first 15 ethusiastic attendees.  We intend to refine this workshop over the GSoC 2024 season and will be running incrementally improving instances weekly in Feb and March.

Check out our [GSoC 2024 Contributors Leaderboard](https://gsoc.rocket.chat/), to see the amazing contributions by our GSoC 2024 community: **45 new contributors with 24 Merged PRs, 50 Open PRs, and 75 Issues** as of **January 15, 2024**!

## 📂 Project Ideas

> This is the GSoC 2024 project ideas list for Rocket.Chat.  As we continue to engage community mentors for 2024, the project ideas are subject to some changes. 

### 💡 Extended LLM Prompt Editor/Explorer

👥 **Mentor(s):** Shubham Bhardwaj

💬 **Description:**

A prompt editor is the quintessential development tool for any  AI/ML prompt engineer.   With ever-increasing number of Rocket.Chat users experimenting and developing with open source LLMs, it is important to have a great prompt editor at their disposal.  This project includes the creation of a fully featured prompt editor as a Rocket.Chat app.   This editor should enable free conversation, by any designated/configured Rocket.Chat user, to chat with any open source LLMs (Mistral,  Llama 2,  Phi, and so on), and the ability to save (and manage - delete etc)  all conversation history.   It should also enable a Rocket.Chat users to "share" the prompt(s) to external applications.   Initial implementation should be for the RC Web App (and Electron).  

💪 **Desired Skills:**  Rocket.Chat Apps development.  LLM prompt editor dev experience.

🎯 **Goals/Deliverables:** Rocket.Chat App empowering users to converse freely with open source LLMs and save the conversations.  The app must allow management of these prompts by the user, including deletion, renaming, and sharing of the prompt content via the clipboard or into the chat stream as a message. 

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡Graphical Guided RC Code Tours

👥 **Mentor(s):** Aditya Singh, Kevin Aleman

💬 **Description:**
Most Rocket.Chat developers uses VSCode when studying our massive production code base, and when writing new code. VSCode is the best environment for conducting interactive tutorial and code walkthroughs. The CodeTour extension available in VSCode can be used to create such walkthrough and tutorials. This project involves the development of a set of guided tutorials using CodeTour that will help new developers to understand how to perform multiple actions. In 2024, we want to extend these tours to include graphical diagrams and flow charts.  

Paths to be documented and graphically enhanced for 2024 include these areas:

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

### 💡News Aggregation App

👥 **Mentor(s):** Abhinav Kumar

💬 **Description:**
A Rocket.Chat app that collects news from top websites like TechCrunch, etc and sends its summary with a link to full content. The technical challenge would be to write different logic to collect news from different sources -> since some has API, some has RSS feed. These sources should be categorized and presented in a "newspaper" or "news feed" format.  News sources and categories should be completely configurable.

💪 **Desired Skills:**
Rocket.Chat App development. 

🎯 **Goals/Deliverables:**
A Rocket.Chat App that can presents users with daily news feed gathered from all over the Internet. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Embedded Chat 2024

👥 **Mentor(s):** Sidharth Mohanty

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

📈 **Difficulty:** Easy


-----

### 💡AI Assistant to help with understanding Rocket.Chat core codebase
👥 **Mentor(s):** Vinayak Sharma 

💬 **Description:**
The code base of Rocket.Chat is known to be unwieldy and large, and typically takes a skilled developer months to become familiar with.    The purpose of this project is to create a Rocket.Chat app that offers an AI assisstant chatbot that can help with the understanding and learning of the Rocket.Chat code base.   This bot should be slash command or GUI accessible and be able to answer structural or logical question about Rocket.Chat's code and how certain workflows are performed within the codebase.  Ideally it should also extract and reference the associated source code lines during its operation.   It is suggested that a Retrieval Augmented Generation pipeline be used to populate a vector database with indexed chunks of the Rocket.Chat code base;  generation should leverage open source LLMs  (Mistral, Llama2, CodeLlama, WizardCode, Phi and so on).  Research and experimentation with chunking strategy, vector search algorithms, and other RAG variables is expected.  

💪 **Desired Skills:**  Rocket.Chat App development. LLM prompt design/engineering.  RAG pipeline design and development.

🎯 **Goals/Deliverables:** A AI assistant chatbot that any Rocket.Chat users can turn to when studying and trying to understand Rocket.Chat's huge codebase.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Easy/Intermediate


-----

### 💡Quick Replies Functionality in RocketChat  

👥 **Mentor(s):** Hugo Costa, Gabriel Casals

💬 **Description:**
Addition of a Quick Replies feature. This functionality would be similar to predefined answers in a helpdesk/support context, giving users the option to generate standardised responses.
Some possible functionality: 
-Allow users to create and save a list of predefined quick replies.
-These quick replies would be accessible through a simple button or keyboard shortcut.
-Users could thus select a quick reply in lieu of manual text input, save time, and expedite the response process.

💪 **Desired Skills:**
Familiarity with react and node; coding on typescript; AI will be a good adition.  

🎯 **Goals/Deliverables:**
Quick Replies feature

⏳ **Project Duration:** 175 hours. (Medium)

📈 **Difficulty:** Intermediate

-----

### 💡AI Query Bot: a configurable Retrieval Augmented Generation pipleline executor 
👥 **Mentor(s):** Shiqi Mei

💬 **Description:**
Create a Rocket.Chat app that answers queries by executing a configurable RAG pipeline.   The RAG pipeline should be configurable via the App's setting - controlling aspects such a embedding/tokenizer engine,  vector database search algorithms, re-ranking strategy,  open source LLM used for generation (Mistral, Llama,  Phi and so on); as well as any prompt used in the pipeline.  The code should have at least two concrete config/examples within two non-trivial problem domains  (feel free to use available public open source data collections).

💪 **Desired Skills:**  Rocket.Chat App development. LLM prompt design/engineering.  RAG pipeline design and development.

🎯 **Goals/Deliverables:** A flexible AI query bot for any problem domain that operates based on a pre-configured RAG pipeline.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡Github App 2024:  Enhanced AI PR summarizer, code reviewer and bug finder 

👥 **Mentor(s):** Samad Khan

💬 **Description:**
Bringing our [Github App](https://github.com/RocketChat/Apps.Github22) into the 2024 AI age, this project will add ability to provide a AI generated summary of PRs to the code reviewers whenever a link is shared for a PR.   The AI assistant should also help in reviewing C/C++, Java, Javascript, or Python code; in addition to help find possible bugs in the code involved.  The app should leverage modern open source LLMs (Mistral, CodeLlama,  WizardCode, Llama2, Phi, and so on) to perform its tasks.     

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**
Github App now leveraging LLMs to perform code review, bug finding, and PR summarization. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy


-----

### 💡 Refactor UI Kit Desktop to improve developer experience (DX)

👥 **Mentor(s):** Carlos Suarez, Gabriel Casals

💬 **Description:**
A UI kit is a set of files that contains critical UI components like fonts, layered design files, icons, documentation, and HTML/CSS files. 
We are looking to make the UI KIT DX better enhancing error boundary, option to send payloads from cloud and render UIKit components, additional input field types and validations

💪 **Desired Skills:**
Familiarity with TypeScript, Javascript and React development

🎯 **Goals/Deliverables:**
Improve UI Kit for Desktop, impacting different areas of Rocket.Chat

⏳ **Project Duration:** 175 hours. (Medium)

📈 **Difficulty:** Intermediate


-----

### 💡AI Bi-directional Translator for Languages, Cultures and Sentiments

👥 **Mentor(s):** Devanshu Sharma (@Dnouv)

💬 **Description:**
Create a Rocket.Chat app that will translate messages within a DM channel between two parties communicating in two different languages.  The app should demostrate not only translation of language, but also account for cultural differences and differences in sentiments.   The app must leverage modern open source LLMs (Mistral, Llama2, Phi, and so on) in generating the translations. 

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**
A Rocket.Chat App that acts as a personal translator for cross-language and cross-cultural communications. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy


-----

### 💡AI in-channel GIF Image Generator 

👥 **Mentor(s):**  Nabhag Motivaras

💬 **Description:**
A slash command triggered Rocket.Chat app that will generate a small GIF image.   The image generation should be controlled via a descriptive prompt issued by the user.  The image can be inserted in-place within the chat or sent to the system clipboard.  The app must leverage modern open source diffusion model such as Stable Diffusion in generating the image. 

💪 **Desired Skills:**
Rocket.Chat App development. Diffusion models prompting.   Artistic inclinations. 

🎯 **Goals/Deliverables:**
A Rocket.Chat App that can generate arbitrary GIF images within a message, based on a descriptive prompt. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Agile BOT

👥 **Mentor(s):** Felipe Scuciatto, Gabriel Casals 

💬 **Description:**
Agile adoption is increasing year to year on the different industries. There is an opportunity to add agile package bots to help squad with reminders, links and facilitate attendance to meeting based on simple calendar inputs and emoji reactions. Candidate will be working with Agile experts and Engineers to build some solutions for this space and help improve team/squads productivity. Successful contributor will propose and implement a Chatbot that solves a problem in agile. Candidate have a free choice of technology to implement the chatbot - RASA, Botpress, Dialogflow, and so on.

💪 **Desired Skills:**
Familiarity with TypeScript development. Demonstrated interest and/or passion in Agile and squad productivity tools.

🎯 **Goals/Deliverables:**
A working chatbot that can improve agile team productivity 

⏳ **Project Duration:** 175 hours. (Medium)

📈 **Difficulty:** Intermediate

-----

### 💡AI Newsletter Generator and Publisher

👥 **Mentor(s):** Sing Li

💬 **Description:**
This Rocket.Chat app leverages modern open source LLMs (Mistral,  Llama2, Phi, and so on) to help generate newsletters for special interest groups and/or teams operating on a Rocket.Chat server.   The newsletter author should be able to supply raw content to the AI generator and have perfectly phrased and formatted newsletter generated.   The app should allow for the immediate or scheduled publication of the resulting newsletter to either a team, subset of the server's user, or all of the server's users.  The app should also allow for emailing those who prefers to receive the newsletter via email.   Ideally the app should maintain a list of dynamically changing newsletter subscribers.

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**
A working Rocket.Chat App that can generate newsletter for a user group or team.  

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Removing meteor-accounts dependency from Rocket.Chat

👥 **Mentor(s):** Debdut Chakraborty

💬 **Description:**
`meteor-accounts` is the largest Meteor dependency Rocket.Chat has as of today. This project will aim to remove all dependency of it from Rocket.Chat taking it further into the road of meteor-less-ness.

💪 **Desired Skills:**
Familiarity with JavaScript and TypeScript is mandatory. Along with server side, may also need client side javascript skills. Meteor knowledge is a plus.

🎯 **Goals/Deliverables:**
Rocket.Chat running without meteor/accounts package as a dependency.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:**  Hard

-----

### 💡AI Chat Conversation Thread Summarizer

👥 **Mentor(s):** José Petry

💬 **Description:**
This Rocket.Chat app leverages modern open source LLMs (Mistral,  Llama2, Phi, and so on) to summarize a conversation within a Rocket.Chat conversation thread.  This summary should appear as either a private message to the invoking user, or become an in-line comment together with the discussion thread itself. 

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**\
A working Rocket.Chat App that can summarize any conversation threads. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Multiple files in one message

👥 **Mentor(s):** Dhruv Jain

💬 **Description:**
Addition of a feature enabling possibility to send multiple files (text files, images, audio, videos) in a same message; similar to what is seen on many other platforms.

💪 **Desired Skills:**
Familiarity with react and node; coding on typescript;

🎯 **Goals/Deliverables:**\
Multiple files in a message feature. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Bluesky AT-protocol Client (and/or ActivityPub) Feeds Aggregator App 

👥 **Mentor(s):** Aaron Ogle

💬 **Description:**
Create a Rocket.Chat app that can be used to aggregate feeds from the Bluesky ecosystem (ActivityPub may need different non-client approach).  User should be able to select and manage the feeds they are interested in.  This project does not involve the posting/publishing of content to the federated networks.

💪 **Desired Skills:**
Familiarity with JavaScript and TypeScript is mandatory. Rocket.Chat app development. Experience or familiarity with AT-protocol or ActivityPub. 

🎯 **Goals/Deliverables:**
Rocket.Chat app that aggregate feeds from Bluesky or Mastodon federated ecosystems.

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:**  Easy/Intermediate

-----

### UIKit Coding Examples and Documentation Improvement

👥 **Mentor(s):** Guilherme Gazzo

💬 **Description:**
Provide a better documentation for the UIkit, adding explanations about the "whys" and "hows". Most importantly, and the coding part of this project: coming up with some non-trivial working examples of concrete use cases.

💪 **Desired Skills:**
Knowledge of TypeScript, JavaScript, React, and Rocket.Chat UIkit.  Previous experience with UI framework or API documentation a big plus.

🎯 **Goals/Deliverables:**

The UIKit documentation improved with many coding examples and an understandable general overview, including:

- Reasons
- Explanation of each Block/Section
- Examples and use cases

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡 Mocks for unit testing : Rocket.Chat Core

👥 **Mentor(s):** Diego Sampaio, Guilherme Gazzo, Tasso Evangelista, Sing Li

💬 **Description:**
This can possibly be the most challenging (and rewarding) project this season, for the "right" candidate.   You will be combing through the massive Rocket.Chat core code base and mapping the critical parts that can be mocked and then implement the injectables for unit testing.

Rocket.Chat is an open source nodeJS based, highly scalable production server that is used by millions daily. Designing and implementing mocks, injectables, and unit testing framework for this sort of scaled server is currently considered pioneering work in open source.   Are you up for the challenge?

💪 **Desired Skills:**
Knowledge of TypeScript, JavaScript, MongoDB, MicroServices, Dependency Injection, and Unit Testing.  Must be passionate about creating test harnesses for modern "impossibly large" real-time server systems. 

🎯 **Goals/Deliverables:**

- Map the critical parts, like collections and services.
- Refactor parts of the codebase that are not injectable yet.
- Create an api/approach to generate mocks for the injectable parts.
- Create a guide for the developers to use the mocks in the unit tests.
- Create a few examples of unit tests using the mocks.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Hard

-----

### 💡 Rocket.Chat Fuselage Components rewrite

👥 **Mentor(s):** Tasso Evangelista, Guilherme Gazzo,  Douglas Fabris

💬 **Description:**
Rewrite the Fuselage components using tha tamagui library. With the objective of improving the performance and the maintainability of the components.
But also allowing the use of the components in different platforms, like React Native.

💪 **Desired Skills:**
Knowledge of TypeScript, JavaScript, React, React Native, and Rocket.Chat Fuselage.

🎯 **Goals/Deliverables:**

- Rewrite the components using the tamagui library.(At least the most used ones)
- Run some of the old projects (rocketchat/livechat/onboarding/uikitplayground) using the new components.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Hard

----- 

### 💡UIKit Playground Translations and Scaffolding

👥 **Mentor(s):**  Douglas Fabris, Guilherme Gazzo, Tasso Evangelista 

💬 **Description:**

Implement the translations in the UIKit Playground, allowing the user to change the language and see the components in different languages, helping to handle the dictionaries and the translations in the UIKit.

Transform all the project in to a scaffold to be used as rocketchat app.

💪 **Desired Skills:**
Knowledge of TypeScript, JavaScript, React, and Rocket.Chat UIKit.

🎯 **Goals/Deliverables:**
- Create a new section in the UIKit Playground to handle the translations.
- Implement the translations in the UIKit Playground.
- Implement code generation for the UIKit Playground to be used as a scaffold for new Rocket.chat apps.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate

-----

### 💡 API Documentation Generator

👥 **Mentor(s):**  Rodrigo Nascimento, Guilherme Gazzo, Diego Sampaio, 

💬 **Description:**
Based on the codebase and typescript definitions, generate the openapi and swagger files.

💪 **Desired Skills:**
Knowledge of TypeScript, JavaScript, and Rocket.Chat API.

🎯 **Goals/Deliverables:**
- Generate the openapi and swagger files, based on the codebase and typescript definitions.
- Provide an automated way to keep the documentation updated.
- Version the documentation based on the Rocket.Chat version.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate

-----

### 💡AI C/C++, Java, Javascript, Typescript, Python Programmer

👥 **Mentor(s):** Mustafa Hasan Khan

💬 **Description:**
Create a Rocket.Chat app that will write short code modules in C/C++, Java, Javascript, Typescript or Python based on specification supplied by the user.   The app should leverage modern open source LLMs (Mistral, CodeLlama,  WizardCode, Llama2, Phi, and so on) to write the code.   The user must be able to quickly reject and ask for a new variation of the code if desired;  the user should also be able to augment/fine-tune the system prompt for more precise code generation (designing an intuitive Ux here can be tricky). Minor editing of generated code should be allowed and easy to make. Finally accepted generated code should be available to be injected into the current channel as a syntax highlighted message, shared to external application, or added to Github (with the associated credentials configured) as a pull request.

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**
A working  Rocket.Chat App that can act as a programming assistant to any developer user of Rocket.Chat.   

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡AI In-message Emoji generator / embellisher

👥 **Mentor(s):** TBD

💬 **Description:**
Create a Rocket.Chat app that will add emoji to an old-school plain text message.  The app should leverage modern open source LLMs (Mistral, Llama2, Phi, and so on) to inject the emojis.   User should be able to adjust the level of embellishment, and should be able to ask for a re-do if needed.  User should be able to make some small edits after emjois are added.  The finally accepted message should be available to be injected into the current channel, shared to external application, or copied to system clipboard.

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**
A Rocket.Chat App that can turn any boring old-school text messages into sensitive modern emojified masterpieces. 

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Multiple Reflect admin actions in a dashboard or audit log

👥 **Mentor(s):** TBD

💬 **Description:**
Administrative change control system in rocket.chat; 
Rocket.Chat admin see if someone change a group name or create a new user, it would be nice if that would be reflected in a dashboard or audit log. This way there would always be a control of what is being done in the production environment at the administrative level.

💪 **Desired Skills:**
Familiarity with react and node; coding on typescript;

🎯 **Goals/Deliverables:**\
Admin Dashboard showing change logs. 

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate


-----

### 💡Multiple Grouping channels in the sidebar into customizable categories

👥 **Mentor(s):** TBD

💬 **Description:**
allow users the ability to create new "custom" sections in the sidebar to be able to group channels, discussions and individual conversations as needed.

💪 **Desired Skills:**
Familiarity with react and node; coding on typescript;

🎯 **Goals/Deliverables:**\
Customizable categories on rocket.chat; better UX. 

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate


-----

### 💡AI Documentation Generator for Code 

👥 **Mentor(s):** TBD

💬 **Description:**
Create an app that will generate documentation for a body of Javascript, Typescript, Python, Java or C/C++ code  (given a github/gitlab URL to the code).   The  app should use modern open source LLMs (Mistral, CodeLlama,  WizardCode, Llama2, Phi, and so on) to generate this documentation.     This documentation should appear either as a private message to the invoking user, as an in-line message for the current channel,  or become available to be shared with external applications. 

💪 **Desired Skills:**
Rocket.Chat App development. LLM prompt design/engineering.

🎯 **Goals/Deliverables:**\
A working Rocket.Chat App that will generate code documentation via AI assistance.

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy


-----

### 💡Removing meteor-accounts dependency from Rocket.Chat

👥 **Mentor(s):** TBD

💬 **Description:**
`meteor-accounts` is the largest Meteor dependency Rocket.Chat has as of today. This project will aim to remove all dependency of it from Rocket.Chat taking it further into the road of meteor-less-ness.

💪 **Desired Skills:**
Familiarity with JavaScript and TypeScript is mandatory. Along with server side, may also need client side javascript skills. Meteor knowledge is a plus.

🎯 **Goals/Deliverables:**
Rocket.Chat running without meteor/accounts package as a dependency.

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡Rocket.Chat configs through a JSON config file (or other format)

👥 **Mentor(s):** TBD

💬 **Description:**
Currently Rocket.Chat can load settings from environment variables named after the setting IDs, like `Account_UseTwofactorEmailAuth` for example (not a literal). 
This poses a fundamental limitation, values of non-string type. This project's aim will be to add another option for Rocket.Chat to load settings' values via a JSON config file like rc.json or some other format (we can discuss).

🎯 **Goals/Deliverables:**
Rocket.Chat starting with a config.json file.

💪 **Desired Skills:**
Basic Typescript knowledge.

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy

-----

### 💡Adding Synapse/Dendrite federation capability to Rocket.Chat Helm Chart

👥 **Mentor(s):** TBD

💬 **Description:**
Currently to enable synapse and matrix federation in a kubernetes cluster, is not very easy task. This project's aim will be to add support for synapse (or dendrite) to be auto deployed much like mongodb is done, behind a flag like `federate: true`.
Understand more the context from https://github.com/RocketChat/federation-airgap - particularly the design and flow documents.

💪 **Desired Skills:**
Kowledge or kubernetes, helm charts, go template language, basic deployment ideas, shell scriptiing

🎯 **Goals/Deliverables:**
A helm chart that can deploy Rocket.Chat with everything configured including Rocket.Chat and a matrix server. This should consider both
- airgapped environments
- public cloud deployments
  
⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate

-----

### 💡NeoVim plugin for Rocket.Chat

👥 **Mentor(s):** TBD

💬 **Description:**
A simple Neovim plugin for Rocket.Chat that one should be able to use for communication, code sharing, simple git processing (sharable).

💪 **Desired Skills:**
Good grip of Lua, knowledge of neovim lua api, neovim api, go/rust may be needed for any external components.

🎯 **Goals/Deliverables:**
Through the plugin, we should be able to
- log in to individual server
- converse with colleagues
- share code lines directly from the editor (blame links, line links etc) and open them as such
- able to collaborate with a team member with ease (member picked from rocket.chat contact list)

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Hard

-----

### 💡VSCode extension for Rocket.Chat

👥 **Mentor(s):** TBD

💬 **Description:**
A simple client in VSCode to have conversations with your team mates through ROcket.Chat.
The goal is for developers to be able to communicate better, which means it will have to provide some simple but different featureset than a normal client. 

💪 **Desired Skills:**
Knowledge of VSCode extension building, TypeScript, Rocket.Chat API.

🎯 **Goals/Deliverables:**
Through the extension, we should be able to
- log in to individual server
- converse with colleagues
- share code lines directly from the editor (blame links, line links etc) and open them as such
- able to collaborate with a team member with ease (member picked from rocket.chat contact list)

⏳ **Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Hard

### 💡Smart Scheduling Assistant App

👥**Mentor(s):** TBD

💬**Description:** Create a Rocket.Chat app that acts as a Smart Scheduling Assistant. The app should be able to understand the context of a conversation, suggest meeting times, send calendar invites, or set reminders based on the chat content. The app should be configurable via the App's settings, allowing customization of the AI's understanding and response generation. The code should include at least two concrete examples of scheduling scenarios.

💪**Desired Skills:** Rocket.Chat App development. LLM prompt development, including function calling (tools pattern).  Experience with calendar APIs (specifically Google Calendar API).

🎯**Goals/Deliverables:** A flexible Smart Scheduling Assistant, fronting Google Calendar, that can understand and respond to scheduling requests in any conversation on Rocket.Chat.

⏳**Project Duration:** 175 hours (Medium)

📈 **Difficulty:** Intermediate



