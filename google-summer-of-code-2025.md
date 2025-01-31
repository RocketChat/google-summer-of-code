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



### 📅  Message Timestamp Date Picker Components

👥 **Mentor(s):** [Martin Schoeler](https://open.rocket.chat/direct/martin.schoeler)

💬 **Description:**
Currently Rocket.Chat has a feature that allows users to send timestamps on messages, but not in an intuitive way. To send a timestamp you need to manually write it down with the correct date code. For example `<t:1732557600:t>`.
This feature was added for Rocket.Chat Apps engine, but users can benefit from this too. The objective of this project is to create a new `MessageToolBar` item that displays a calendar and let the users select the date and time they would like to share, both in the desktop app and mobile apps.

Some examples of the usage of the timestamp feature (you can test them today on the open.rocket.chat server!)

Pattern: <t:{timestamp}:?{format}>

- {timestamp} is a Unix timestamp
- {format} is an optional parameter that can be used to customize the date and time format.

**Formats**

| Format | Description               | Example                                 |
| ------ | ------------------------- | --------------------------------------- |
| `t`    | Short time                | 12:00 AM                                |
| `T`    | Long time                 | 12:00:00 AM                             |
| `d`    | Short date                | 12/31/2020                              |
| `D`    | Long date                 | Thursday, December 31, 2020             |
| `f`    | Full date and time        | Thursday, December 31, 2020 12:00 AM    |
| `F`    | Full date and time (long) | Thursday, December 31, 2020 12:00:00 AM |
| `R`    | Relative time             | 1 year ago                              |

The creation of tests for the new component is also expected, both end to end and unit if applicable.

💪 **Desired Skills:** React, Typescript, React Native

🎯 **Goals/Deliverables:** A new component on the `MessageToolBar` that allows users to add timestamps to their messages, both in desktop and mobile.

⏳ **Project Duration:** 90 hours. (Small)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡Embedded Chat 2025

👥 **Mentor(s):** Zishan Ahmad

💬 **Description:**
Improvement to the EmbeddedChat project this year includes:
- Upgrading the current API and auth packages to use the latest Rocket.Chat SDK packages like `ddp-client`, and aligning other components to use other abstraction provided by Rocket.Chat, ensuring these packages will be managed internally moving forward.
- Making the EmbeddedChat fully mobile-responsive for a seamless experience across all devices.
- Improving the UI and adding more customization options to enhance the user experience.

💪 **Desired Skills:**
React.Js

🎯 **Goals/Deliverables:**
- Integration of the latest Rocket.Chat SDK packages
- Fully mobile-responsive EmbeddedChat
- Improved UI with more customization options

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡 Rocket.Chat Docs Assistant (RAG-based AI Search)

👥 **Mentor(s):** Devanshu  

💬 **Description:**  
This project aims to build a Rocket.Chat App that provides a **natural language interface** for querying Rocket.Chat Docs (docs.rocket.chat). Instead of manually searching for answers, users can simply ask the app, and it will return a **relevant, structured response** based on the documentation.  

Key Features:  
- **Retrieval-Augmented Generation (RAG)** approach to search and retrieve docs.  
- **Local embedding model** (running on CPU) to generate query representations.  
- **In-memory vector store** to efficiently match queries to relevant documentation.  
- **Context-aware responses** to handle follow-up questions naturally.  

💪 **Desired Skills:**  
- Rocket.Chat Apps Engine (TypeScript)  
- Natural Language Processing (NLP)  
- Vector search (HNSW, LSH, or similar techniques in JS)  
- Web Storage & IndexedDB (for caching, if needed)  

🎯 **Goals/Deliverables:**  
- A Rocket.Chat App that enables users to query Rocket.Chat Docs via natural language.  
- **Efficient RAG-based retrieval** with an in-memory vector store.  
- A **lightweight, CPU-friendly embedding model** for query similarity matching.  
- **Interactive chat interface** that tracks context for follow-up queries.  

⏳ **Project Duration:** 90 hours (Small)  

📈 **Difficulty:** Intermediate/Advanced  

---
