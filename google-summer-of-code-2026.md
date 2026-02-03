# Google Summer of Code 2026

## [![Google Summer of Code 2026](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com)

## How to apply

Rocket.Chat applied as a mentoring open source organization for Google Summer of Code 2026.  See [official Google Summer of Code site](https://summerofcode.withgoogle.com/).

Rocket.Chat is always proud to be involved with the Google Summer of Code program, helping to usher in a new generation of global open source contributors and enthusiasts.

Join our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026) and introduce yourself to the rapidly growing community of 640+ right now! 

For timeline, see [Official Google Summer of Code 2026](https://developers.google.com/open-source/gsoc/timeline) Timeline for more details.

Almost anyone in the world [over 18 years of age](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) who loves coding and wants to explore the incredible world of open source can join us as a GSoC 2026 contributor.

Most exciting news for the 2026 season is continued focus on ML/AI projects, and the continued support for a small project size with a 90 hours duration; allowing participation from those who can only devote part of their summer to exploring open source.

For details and rules of Google Summer of Code 2026, please see the [GSoC 2026 Official Website](https://summerofcode.withgoogle.com/). For timeline, see [Official Google Summer of Code 2026 Timeline](https://developers.google.com/open-source/gsoc/timeline) for more details.

If you intend to use AI to assist you in the creation of your project proposal, please be aware that we will not be accepting any proposals that is directly created by an LLM or Agentic AI tooling.   The proposal must be crafted by you personally (OK to use AI for research, translation, and so on) and you must be ready to defend every line of its content when/if we contact you for a meeting.  You should also be engaged within our community (active on our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026), attend our weekly tea time, take our live workshops, and so on) and have auditable Github activity to increase the probability of your proposal being considered for GSoC 2026.   See [Google's Contributors Guide on using AI tooling in GSoC 2026](https://docs.google.com/document/d/1t9GcIBnNXPNO6klRQvU8pL8-uV6afzLo6JUAM299suA/edit?tab=t.0#heading=h.tgbr0z4x9eg5) for some suggestions.

### **Contacting Rocket.Chat**

For general information, please visit our 24 x 7 community channel for Google Summer of Code 2026 : [https://open.rocket.chat/channel/opensource2026](https://open.rocket.chat/channel/opensource2026)

Join our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026) today, introduce yourself to the friendly community, and interact with over **638 like-minded** contributors/mentors (as of January 27, 2025) and meet the team in the [12+ team channels](https://open.rocket.chat/channel/opensource2026/team-channels).

Interested contributors are also encouraged to interact directly with our team and community on the team channels:

[https://open.rocket.chat/channel/opensource2026/team-channels](https://open.rocket.chat/channel/opensource2026/team-channels)

As well as on GitHub:

[https://github.com/RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)

Those who prefers forums can post messages on our GSoC forum channel (although as the leading open source team chat project we prefer you use Rocket.Chat channels above to reach us instantly).

---

### **Latest update**
As of **January 27, 2026**  we have welcomed *638* open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).  We have released an initial [2026 ideas list](https://github.com/RocketChat/google-summer-of-code/blob/main/google-summer-of-code-2026.md#-project-ideas) and are now talking with mentors (many returning former GSoC participants) on expanding the list with interesting projects   Thanks to everyone for their interest and ethusiasm on open source, and looking forward to meet everyone at our tea time on Fridays.

As of **January 8, 2026**  we have welcomed *470* open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).  We want to thank everyone for their interest and ethusiasm on open source, and looking forward to meet everyone at our tea time on Fridays.


As of **December 7, 2025**  we started to welcome open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).

## 📂 Project Ideas   

(This list is going through some rapid changes as mentors and community members discuss content and approaches to realize them within the GSoC timeframe.)


### 💡 High-Performance Message Parser Rewrite

👥 **Mentor(s):** Matheus Cardoso  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace

💬 **Description:**
The current Rocket.Chat [message parser](https://github.com/RocketChat/Rocket.Chat/tree/develop/packages/message-parser) relies on [PeggyJS](https://github.com/peggyjs/peggy) (formerly [PEG.js](https://github.com/pegjs/pegjs)). While effective, the generated parser creates performance bottlenecks and adds significant bundle size overhead.
The goal of this project is to replace the PeggyJS-generated parser with a highly optimized, hand-written TypeScript implementation (or using a toolkit like [Chevrotain](https://github.com/Chevrotain/chevrotain). The new implementation must produce the exact same Abstract Syntax Tree (AST) structure as the current one but with a focus on **speed**, **type safety**, and **modularity**.

💪 **Desired Skills:**

* TypeScript
* Algorithms & Data Structures (Context-Free Grammars, Recursive Descent)
* Performance Profiling & Benchmarking
* Property-based Testing (e.g., fast-check)

🎯 **Goals/Deliverables:**

* **Core Implementation:** A functional, drop-in replacement parser in pure TypeScript.
* **100% Parity:** Pass all existing unit tests (`message-parser/tests/*.test.ts`) to guarantee backward compatibility.
* **Robustness:** Implement **Fuzz Testing** (property-based testing) to ensure the parser handles edge cases and malformed inputs without crashing.
* **Performance:** Create a benchmark suite demonstrating significant improvements in **ops/sec** and a reduction in **bundle size**.

⏳ **Project Duration:**
175 hours

📈 **Difficulty:**
Medium

---

### 💡 Refactor Virtualized Lists to Use TanStack Virtual

👥 **Mentor(s):** Martin Schoeler, Douglas Fabris  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Replace existing Virtuoso based virtual lists with a standardized implementation using TanStack Virtual, ensuring consistent behavior and performance.

💪 **Desired Skills:**  
- React  
- TypeScript  
- Jest or Playwright  

🎯 **Goals/Deliverables:**  
- Refactor all virtual list implementations  
- Maintain feature parity with tests  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Embedded Chat 2026

👥 **Mentor(s):** Zishan Ahmad

📢 **Communication Channel:** Rocket.Chat Contributors Workspace

💬 **Description:**
This project improves EmbeddedChat by keeping it compatible with the latest Rocket.Chat releases, adding support for homeserver and federation features, and introducing a pluggable AI adapter layer. It also focuses on better mobile usability, improved accessibility, and welcoming practical improvements to the overall experience.

💪 **Desired Skills:**

- Strong understanding of Rocket.Chat APIs and SDKs
- Experience with React.js and Node.js
- Familiarity with UI design and responsive layouts
- Interest in accessibility standards and best practices
- Understanding of AI integrations is a plus

🎯 **Goals/Deliverables:**


- Update Rocket.Chat APIs and SDKs, then update React, Node, and related packages to the latest versions so EmbeddedChat works with current Rocket.Chat releases.
- Upgrade EmbeddedChat for compatibility with Rocket.Chat homeserver capabilities, including Matrix federation and bridged rooms.
- Add a pluggable adapter to connect EmbeddedChat with local or external AI through an integrator-controlled layer, enabling smart widget features beyond core.
- Improve EmbeddedChat UI and the native app to achieve better mobile responsiveness.
- Add WCAG compliance, keyboard navigation, and automated accessibility testing across all components.
- Welcoming any other creative ideas that improve the project.

⏳ **Project Duration:** 175 hours

📈 **Difficulty:** Medium

---

### 💡 AI Generated Regression Test Suite for Desktop (Electron) App

👥 **Mentor(s):**  Harmeet Kour, Jessica Souza  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**   
In this project, the contributor will build a full coverage test suite for our Desktop (Electron) App with the help of the latest available open source mainstream AI code generation tooling (Gemini cli or OpenCode). Mentors will help in scoping the coverage and enumeration of the essential cases, as well as guiding for best practices in test suite creation, CI integration, and QA in general. 

🎯 **Goals/Deliverables:** 
Our Desktop App (Electron) project is currently in need of a full coverage test suite.  This will add the essential test suite to ensure the project's maintainability and long term stability. 

💪 **Desired Skills:**  
- Electron and JavaScript
- Familiarity with our Desktop App and TypeScript development
- Must already be experienced with mainstream open source (AI) code generation technology

⏳ **Project Duration:**  
90 hours

📈 **Difficulty:** 
Medium

-----

💡 Mobile Apps: Notifications Improvements

👥 **Mentor(s):** Rohit Bansal  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Improve the overall push notification experience on mobile by enhancing notification content, reducing noise, and ensuring outdated notifications are automatically removed from the system Notification Center.

The project focuses on improving clarity, usability, and correctness of notifications across iOS and Android platforms.

💪 **Desired Skills:**  
- React Native
- TypeScript
- Native iOS & Android notification handling
- Backend API design

🎯 **Goals/Deliverables:**  
- Display attachments in push notifications where supported
- Trim reply and quote content in notifications to improve readability
- Support replying in threads directly from notifications
- Display thread context in push notification content
- Reduce notification clutter in the system Notification Center
- Implement a backend endpoint that receives message IDs, determines their read/unread state and integrates this logic to automatically clear read notifications from the Notification Center

⏳ **Project Duration:**
175 hours

📈 **Difficulty:**  
Medium

-----

### 💡 Activity Hub

👥 **Mentor(s):** Pierre Lehnen, Milton Rucks  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Build a new screen on the rocket.chat client  where users can see a history of their recent notifications and mentions, with options to manually remove items from this history or to clear the whole history at any time. Additionally, show a list of all of the user’s starred messages from every channel.

💪 **Desired Skills:**  
- React
- Typescript (Backend and Frontend)

🎯 **Goals/Deliverables:**  
Make it easier for users to keep track of recent messages or messages that they have already read but still want to keep a reference to for quick access in the near future.

⏳ **Project Duration:**  
175 hours

📈 **Difficulty:** 
Medium

---

### 💡 Desktop App: Multiple Conversation Tabs

👥 **Mentor(s):** Jean Brito, Felipe Scuciatto  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Enhance the Rocket.Chat Electron desktop app by introducing multi conversation tab support, allowing users to open and manage multiple channels, DMs, or threads simultaneously.

💪 **Desired Skills:**  
- React  
- TypeScript  
- Electron  

🎯 **Goals/Deliverables:**  
- Tabbed conversation interface  
- Improved productivity for power users  
- Reduced friction when switching contexts  

⏳ **Project Duration:**  
90 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Agenda Jobs Admin Page

👥 **Mentor(s):**  Kevin Aleman, Douglas Gubert  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Create an admin interface to visualize and manage all Agenda scheduled jobs, including execution history, failures, and administrative actions.

💪 **Desired Skills:**  
- React  
- TypeScript  
- Node.js  
- MongoDB  

🎯 **Goals/Deliverables:**  
- Admin UI for scheduled jobs  
- Failure visibility and execution history  
- Quick administrative actions  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Required Role per Channel for Membership Control

👥 **Mentor(s):** Gabriel Casals  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Introduce channel level RBAC by allowing admins or channel leads to define a required role for channel membership. Users without the role cannot be added and receive a clear error message.

💪 **Desired Skills:**  
- Node.js  
- MongoDB  
- Authorization and RBAC concepts  

🎯 **Goals/Deliverables:**  
- Channel level required role configuration  
- Enforcement on membership flows  
- Audit logs and admin UI  

⏳ **Project Duration:**  
90 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Personal Calendar

👥 **Mentor(s):** Pierre Lehnen  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Create a new interface that allows users to view and manage their personal Rocket.Chat calendar directly within the product, expanding and integrating the existing backend calendar system.

💪 **Desired Skills:**  
- React  
- TypeScript  
- Frontend focused development  

🎯 **Goals/Deliverables:**  
- Manage calendar events inside Rocket.Chat  
- Support internal and optional external calendars  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Rebuilding the Jira Integration App for Rocket.Chat

👥 **Mentor(s):** Felipe Scuciatto  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Rebuild and modernize the Jira integration app for Rocket.Chat, restoring a critical productivity feature that enables users to work with Jira issues directly from chat.

💪 **Desired Skills:**  
- Rocket.Chat Apps Engine  
- TypeScript  

🎯 **Goals/Deliverables:**  
- Fully functional Jira Marketplace app  
- Issue interaction inside Rocket.Chat  

⏳ **Project Duration:**  
90 hours  

📈 **Difficulty:**  
Medium  

---


### 💡 Apps Engine Test Framework for Apps

👥 **Mentor(s):** Douglas Gubert    
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Introduce a test framework for Rocket.Chat Apps Engine to simplify unit and integration testing by providing standardized mocks and scaffolding.

💪 **Desired Skills:**  
- TypeScript  
- Node.js  

🎯 **Goals/Deliverables:**  
- Improved testing experience for app developers  
- Standardized testing utilities  
- Support for integration tests  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Room Header Buttons Ordering

👥 **Mentor(s):** Milton Rucks, Martin Schoeler  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Implement a configurable layout engine for the room header that allows administrators to explicitly define the display order of action buttons. This enables pinning high priority actions directly in the main toolbar while organizing secondary actions in the overflow (ellipsis) menu based on organizational needs.

💪 **Desired Skills:**  
- React  
- TypeScript  
- UI layout systems  

🎯 **Goals/Deliverables:**  
- Reduce UI clutter in room headers  
- Surface high priority actions more effectively  
- Improve user efficiency  

⏳ **Project Duration:**  
90 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Ephemeral Messages

👥 **Mentor(s):** TBD    
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
A feature enabling users to send self destructing messages that automatically and permanently delete themselves from chat history and the server after a specified duration or once viewed by the recipient.

💪 **Desired Skills:**  
- Node.js  
- Message lifecycle management  
- Security and privacy concepts  

🎯 **Goals/Deliverables:**  
- Time based and view based message expiration  
- Improved privacy for sensitive data sharing  
- Reduced long term chat clutter  

⏳ **Project Duration:**  
350 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Sidebar Custom Grouping

👥 **Mentor(s):** TBD  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Allow users to create custom, collapsible folders or sections in the sidebar to manually organize channels, direct messages, and other conversations.

💪 **Desired Skills:**  
- React  
- TypeScript  
- UX focused feature design  

🎯 **Goals/Deliverables:**  
- Better workspace navigation  
- Reduced information overload  
- User controlled prioritization  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Warning and Reporting for Login Attempts from Inactive or Deactivated Users

👥 **Mentor(s):** TBD  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Detect and report authentication attempts from inactive (180+ days) or deactivated user accounts, generating real time alerts and periodic risk reports for administrators.

💪 **Desired Skills:**  
- Node.js  
- Authentication and authorization systems  
- Security and audit logging  

🎯 **Goals/Deliverables:**  
- Detection of suspicious login attempts  
- Admin alerts and risk reports  
- Audit and compliance support  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 New Users Anti Spammer System

👥 **Mentor(s):**  TBD  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  
Build an AI assisted system that monitors new users during their first 6 to 10 weeks, detecting spam patterns and suspicious behavior to protect communities and reduce manual moderation.

💪 **Desired Skills:**  
- Node.js  
- Rule based or ML detection systems  
- Trust and safety concepts  

🎯 **Goals/Deliverables:**  
- Behavioral analysis of new users  
- Automated moderation actions  
- Daily risk scoring and reporting  

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Replace old Rest Api definitions over the new API

👥 **Mentor(s):**  @diego.sampaio @guilherme.gazzo  
📢 **Communication Channel:** Rocket.Chat Contributors Workspace  


💬 **Description:**  
The goal of this project is to continue the migration of our REST typings to the new API format.
This new format not only standardizes API definitions, but also enables automatic generation of OpenAPI documentation directly from the type definitions.

In addition to the typings migration, the project also includes architectural adaptations to support like: A clear separation between route definitions and their corresponding actions/handlers

💪 **Desired Skills:**  
- Typescript

⏳ **Project Duration:**  
350 hours  

📈 **Difficulty:**  
Medium  