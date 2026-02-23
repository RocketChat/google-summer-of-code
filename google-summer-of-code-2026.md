# Google Summer of Code 2026

## [![Google Summer of Code 2026](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com)

## How to apply

Rocket.Chat is proud to be a participating mentoring open source organization for [Google Summer of Code 2026](https://summerofcode.withgoogle.com/). helping to usher in a new generation of global open source contributors and enthusiasts.

Join our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026) and introduce yourself to the rapidly growing community of 800+ right now! 

For timeline, see [Official Google Summer of Code 2026](https://developers.google.com/open-source/gsoc/timeline) Timeline for more details.

Almost anyone in the world [over 18 years of age](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) who loves coding and wants to explore the incredible world of open source can join us as a GSoC 2026 contributor.

Most exciting news for the 2026 season is continued focus on ML/AI projects, and the continued support for a small project size with a 90 hours duration; allowing participation from those who can only devote part of their summer to exploring open source.

For details and rules of Google Summer of Code 2026, please see the [GSoC 2026 Official Website](https://summerofcode.withgoogle.com/). For timeline, see [Official Google Summer of Code 2026 Timeline](https://developers.google.com/open-source/gsoc/timeline) for more details.

If you intend to use AI to assist you in the creation of your project proposal, please be aware that we will not be accepting any proposals that is directly created by an LLM or Agentic AI tooling.   The proposal must be crafted by you personally (OK to use AI for research, translation, and so on) and you must be ready to defend every line of its content when/if we contact you for a meeting.  You should also be engaged within our community (active on our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026), attend our weekly tea time, take our live workshops, and so on) and have auditable Github activity to increase the probability of your proposal being considered for GSoC 2026.   See [Google's Contributors Guide on using AI tooling in GSoC 2026](https://docs.google.com/document/d/1t9GcIBnNXPNO6klRQvU8pL8-uV6afzLo6JUAM299suA/edit?tab=t.0#heading=h.tgbr0z4x9eg5) for some suggestions.

### **Contacting Rocket.Chat**

For general information, please visit our 24 x 7 community channel for Google Summer of Code 2026 : [https://open.rocket.chat/channel/opensource2026](https://open.rocket.chat/channel/opensource2026)

Join our [Google Summer of Code 2026 Team ](https://open.rocket.chat/channel/opensource2026) today, introduce yourself to the friendly community, and interact with over **800 like-minded** contributors/mentors (as of February 17, 2026) and meet the team in the [12+ team channels](https://open.rocket.chat/channel/opensource2026/team-channels).

Interested contributors are also encouraged to interact directly with our team and community on the team channels:

[https://open.rocket.chat/channel/opensource2026/team-channels](https://open.rocket.chat/channel/opensource2026/team-channels)

As well as on GitHub:

[https://github.com/RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)

Those who prefers forums can post messages on our GSoC forum channel (although as the leading open source team chat project we prefer you use Rocket.Chat channels above to reach us instantly).

---

### **Latest update**

As of **February 17, 2026**  we have welcomed *800* open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).  Over *68* contributors have already signed up for our [open source contribution leaderboard](https://gsoc.rocket.chat) and contributed 14 Merged PRs, 155 Open PRs, and 113 Issues!  Our [2026 ideas list](https://github.com/RocketChat/google-summer-of-code/blob/main/google-summer-of-code-2026.md#-project-ideas) is now live and mentors (many returning former GSoC participants) are finalizing details of the projects.  We are meeting everyone at a live tea time every Friday and just announced a live workshop on App creation that community members can participate in.    Thanks to everyone for their interest and ethusiasm on open source.

As of **January 27, 2026**  we have welcomed *638* open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).  We have released an initial [2026 ideas list](https://github.com/RocketChat/google-summer-of-code/blob/main/google-summer-of-code-2026.md#-project-ideas) and are now talking with mentors (many returning former GSoC participants) on expanding the list with interesting projects   Thanks to everyone for their interest and ethusiasm on open source, and looking forward to meet everyone at our tea time on Fridays.

As of **January 8, 2026**  we have welcomed *470* open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).  We want to thank everyone for their interest and ethusiasm on open source, and looking forward to meet everyone at our tea time on Fridays.


As of **December 7, 2025**  we started to welcome open source contributors from all over the world, new to Rocket.Chat, to join us for preparation of GSoC 2026 in our [community channel](https://open.rocket.chat/channel/opensource2026).

## 📂 Project Ideas   

(This list is going through some rapid changes as we work with mentors to fully flesh out the project ideas.)


### 💡 High-Performance Message Parser Rewrite

👥 **Mentor(s):** Matheus Cardoso  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-High-Performance-Message-Parser-Rewrite)

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

### 💡 AI Rocket.Chat Apps Generator 

👥 **Mentor(s):**   Dnouv    
📢 **Communication Channel:**   [team channel](https://open.rocket.chat/channel/idea-AI-Rocket-Chat-Apps-Generator)

💬 **Description:**  
This is a set of extension (or a fork) of open source `gemini-cli` that will facilitate anyone to create/generate their own  Rocket.Chat app with ease. 

The tool must have built-in internal knowledge of the architecture of a Rocket.Chat App, how to build and test an App,  and how to generate ALL the elements that an App can use to interface with the Apps Engine/server (bridged APIs, web hooks, persistence, per-user state management and so on).     

The tool should also be able to generate and maintain tests for the created App.

💪 **Desired Skills:**  
* Experience with modern code generation cli (Claude Code, OpenCode, OpenAI Codex, `gemini-cli` and so on ) 
* A passion for creating tooling for AI coding  
* Familiarity with Rocket.Chat App creation and Apps Engine operation
* TypeScript development 
* `gemini-cli` architecture and extension mechanisms 
* Prompt engineering

🎯 **Goals/Deliverables:**  
A very easy to use and understand CLI tool that anyone can use to create, test, and deploy their own custom Rocket.Chat apps. 

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---


### 💡 Refactor Virtualized Lists to Use TanStack Virtual

👥 **Mentor(s):** Martin Schoeler, Douglas Fabris  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Refactor-Virtualized-Lists-to-Use-TanStack-Virtual)  

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

### 💡 Rocket.Chat Code Analyzer: agentic inference context reduction mechanics 
👥 **Mentor(s):**   William Liu  
📢 **Communication Channel:**  [team channel](https://open.rocket.chat/channel/idea-Rocket-Chat-Code-Analyzer)   

💬 **Description:**  
Most production codebases are stored in huge revision control repositories (similar to Rocket.Chat) and  are often monorepos that combines the source code of a large number of related subprojects.  

When AI agentic tooling is unleashed on these huge code repositories, it quickly reveals the primitive and wasteful (unoptimized) nature of early tools.    Because LLM inferences are being performed inside a loop where the context of the queries are being built; and the context is constantly increasing in size, query after query.    

This means that repositories as large as Rocket.Chat is often out of reach (of the token/AI-inference budget) for many open source developers.  Even though some AI service providers offer per-session caching and compression (llmlinqua and so on), these are O(n) optimizations that have only nominal impact on the overall project/session cost when large repositories are involved.  

This project explores and implements a class of “domain specific context reduction mechanisms” that can  have exponential impact when working with large code repositories.  These scoping mechanisms are specific to (works only with)  the domain of “code analysis/generation”.  

The project’s code will be an extension or fork of `gemini-cli`,  with the context reduction mechanism added.   It will enable users of `gemini-cli`  to work with (analyze, or generate code based on ) the (known to be huge) Rocket.Chat’s monorepo, all within the budget of the “free tier” inference currently offered by Google.       
Ideally, the mechanics should be implemented in a re-usable manner, extending its utility to other large codebases and the contributor can contribute it back upstream to `gemini-cli`. 

💪 **Desired Skills:**   
* A passion for innovations on open source tooling for the age of open source AI  (vibe) coding 
* Experience with modern code generation cli - Claude Code, OpenCode, OpenAI Codex, gemini-cli and so on
* Intimate understanding of how  gemini-cli works  — Familiarity with Rocket.Chat’s codebase in our monorepo
* TypeScript development 
* Coding with `gemini-cli` extension mechanisms 
* Prompt engineering 
* Theoretical understanding of agentic systems and LLM inference 

🎯 **Goals/Deliverables:**   
Tooling that enables open source AI developers to work with huge production code repositories, within industry provider’s free-tier limits; opening access of these great tools to an exponentially larger population of users.    

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Embedded Chat 2026

👥 **Mentor(s):** Zishan Ahmad

📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Embedded-Chat-2026)

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

### 💡 Replace old Rest Api definitions over the new API

👥 **Mentor(s):**  @diego.sampaio @guilherme.gazzo  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Replace-old-REST-API-definitions-over-the-new-API) 


💬 **Description:**  
The goal of this project is to continue the migration of our REST typings to the new API format.
This new format not only standardizes API definitions, but also enables automatic generation of OpenAPI documentation directly from the type definitions.

In addition to the typings migration, the project also includes architectural adaptations to support like: A clear separation between route definitions and their corresponding actions/handlers

💪 **Desired Skills:**  
* Typescript

⏳ **Project Duration:**  350 hours  

📈 **Difficulty:**  Medium  

---

### 💡 OpenClaw Integration for Rocket.Chat

👥 Mentor(s): Jeffrey Yu

📢 Communication Channel: ** [team channel](https://open.rocket.chat/channel/idea-OpenClaw-Integration-for-Rocket-Chat)

💬 Description:  
[OpenClaw](https://openclaw.ai/) (previously named **Clawdbot**) is a fast-growing open-source autonomous AI agent. Unlike traditional prompt-response chatbots, OpenClaw focuses on proactive, autonomous task execution — such as managing workflows, triaging inboxes, orchestrating tools, or generating code — by combining LLM reasoning with real tool integrations. This agent-driven paradigm has led to strong adoption in the open-source community.

The essential interaction layer of OpenClaw allows users to control and supervise the agent conversationally through messaging apps. Currently, OpenClaw [supports](https://docs.openclaw.ai/channels/telegram) messaging platforms like Telegram and WhatsApp, while there is a surging [community demand](https://github.com/openclaw/openclaw/issues/7520) for Rocket.Chat integration.

This project aims to implement Rocket.Chat integration for OpenClaw. This tool will enable users to interact with autonomous AI agents directly from Rocket.Chat DMs and channels.

🛠️ Desired Skills:

- TypeScript / Node.js
- Experience building webhook-based integrations and handling realtime messaging events
- Familiarity with OpenClaw and Rocket.Chat Apps / APIs
- Understanding of authentication and secure token handling

🎯 Goals:

- Support direct messages and slash-command channel conversations for OpenClaw
- Enable secure configuration and authentication flow with role-based access control

⏳ Project Duration: 175 hours

📊 Difficulty: Medium

---

### 💡 Minimal MCP Server Generator for Rocket.Chat

👥 **Mentor(s):**  Hardik Bhatia  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Minimal-MCP-Server-Generator-for-Rocket-Chat)   

💬 **Description:**
This is an extension/customization of open source `gemini-cli` that will generate a production-ready MCP server, together with tests,  for any subset of Rocket.Chat APIs specified. 

MCP is high level alternative protocol used for LLM function calling (tools calling) that Anthropic had trained their LLM to excel in.  MCP has been adopted on a viral scale by many developers transitioning to AI Code generation.  Most recently, all major frontier models providers/platformers have caught up and supported MCP;  and Anthropic has donated the protocol to the Linux Foundation.    

Today, one major problem when adopting MCP is that it is originally designed to reward the inference platform provider.  Almost all MCP servers are written to support a large set of services APIs that covers the functionality of the specific service provider (usually tightly coupled with an associated platform provider).  And anyone adopting multiple MCP servers will experience “context bloat”  where most of their token budget and context-content is consumed by static MCP requirements; associated with API calls that they will never need or use within their project.  This situation is exacerbated  in agentic code generator workflows where every agent is burning token in loops unnecessarily while supporting API/tools that the project will never need.

Rocket.Chat will solve this problem with this Minimal MCP Server Generator project.  With this tool, Rocket.Chat developers can generate production grade minimal MCP server for their project, covering only the subset of API required by the project.   This will significantly reduce the cost of all Rocket.Chat code generation projects involving MCP.  Since Rocket.Chat is open source, this tool can make many projects possible by fitting into the “free tier” of the platform providers.  

Candidate is encouraged to solve this problem more generically while fulfilling all Rocket.Chat’s requirements.  Ideally, the tool can benefit all similar upstream projects/platforms, open source or otherwise. 

💪 **Desired Skills:**  
* A passion for creating innovative tooling for AI (Vibe 2.0) coding 
* Experience with modern code generation cli : Claude Code, OpenCode, OpenAI Codex, gemini-cli and so on
* Experience with creation  of (or working with) MCP servers
* TypeScript development 
* gemini-cli architecture and extension mechanisms 
* Prompt engineering

🎯 **Goals/Deliverables:**   
A tool to generate a minimal-cover MCP server for anyone developing with Rocket.Chat who also needed MCP support.  This can greatly reduce the cost, while increasing the stability and reliability of agentic code generation process.

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 AI Generated Regression Test Suite for Desktop (Electron) App

👥 **Mentor(s):**  Harmeet Kour, Jessica Souza  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-AI-Generated-Regression-Test-Suite-for-Desktop-Electron-App)  

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

### 💡 Mobile Apps: Notifications Improvements

👥 **Mentor(s):** Rohit Bansal    
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Mobile-Apps-Notifications-Improvements) 

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

### 💡 Mobile Apps: Use bottom tabs navigation

👥 **Mentor(s):** Diego Mello  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Mobile-Apps-Use-bottom-tabs-navigation)

💬 **Description:**  
We're currently using sidebar navigation on the app, but we have plans to apply bottom tabs navigation to improve UX.

💪 **Desired Skills:**  
- React Native
- TypeScript

🎯 **Goals/Deliverables:**  
We'll have to iterate around which tabs works best, a first execution of this would consider:
- Home tab: List of all channels except discussions and DMs
- Discussions tab: Only discussions
- DMs: Only DMs
- More: Display everything that's on Settings currently
- Search: We would move search to the tabs, so it follows new pattern of iOS 26

Currently the workspace selection is done by tapping the workspace name on the main screen.
We should move it to the sidebar.

⏳ **Project Duration:**
175 hours

📈 **Difficulty:**  
Medium

-----

### 💡 Custom mentions

👥 **Mentor(s):** Diego Mello  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Custom-mentions)  

💬 **Description:**  
Allow the creation of new mentions targetting a specific set of users.
This is very useful when you need to notify a group of people, but don't want to use `@all` or `@here`.
While this can be technically achieved using teams feature, it's a little bit too much work for a simple communication win.

A room with engineers could have custom mentions for `@backend`, `@frontend`, `@sre`, `@mobile`, `@em`, etc.
A group of people that was involved on a project could have `@project-abc`.

💪 **Desired Skills:**  
- React
- React Native
- TypeScript

🎯 **Goals/Deliverables:**  
- Allow custom mentions on web
- Allow custom mentions on mobile
- Display a list of people that belonged to the team when the message was sent
- Add `Custom mentions` to admin panel

⏳ **Project Duration:**
175 hours

📈 **Difficulty:**  
Medium

-----

### 💡 Activity Hub

👥 **Mentor(s):** Pierre Lehnen, Milton Rucks  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Activity-Hub)  

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Desktop-App-Multiple-Conversation-Tabs) 

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Agenda-Jobs-Admin-Page)  

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Required-Role-per-Channel-for-Membership-Control) 

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Personal-Calendar)

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Rebuilding-the-Jira-Integration-App-for-Rocket-Chat) 

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
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-App-Engine-Test-Framework-for-Apps)

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

### 💡 Warning and Reporting for Login Attempts from Inactive or Deactivated Users

👥 **Mentor(s):** Abhinav Kumar  
📢 **Communication Channel:** [Team Channel](https://open.rocket.chat/channel/idea-Warning-and-Reporting-for-Login-Attempts-from-Inactive-or-Deactivated-Users) 

💬 **Description:**  
Detect and report authentication attempts from inactive (180+ days) or deactivated user accounts. Generate real-time alerts and periodic risk reports for administrators, including notifications for failed login attempts.

💪 **Desired Skills:**  
- Node.js/TypeScript
- Authentication & authorization systems
- Security & audit logging
- MongoDB & React  

🎯 **Goals/Deliverables:**  
- Suspicious Login Detection: Monitor logins from inactive/deactivated accounts
- Real-time Alerts: DM and email notifications to admins
- Admin Dashboard: Visual metrics, attempt history, quick actions
- Audit Logging: Comprehensive security logs for compliance
- Periodic Reports: Automated weekly/monthly risk reports
- Failed Attempt Tracking (Bonus): Log failed logins, detect brute force patterns

⏳ **Project Duration:**  
175 hours  

📈 **Difficulty:**  
Medium  

---

### 💡 Room Header Buttons Ordering

👥 **Mentor(s):** Milton Rucks, Martin Schoeler  
📢 **Communication Channel:** [team channel](https://open.rocket.chat/channel/idea-Room-Header-Buttons-Ordering)  

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

### 💡 Tamagui-Based Refactor of Fuselage Components: Bundle Size and Performance Analysis

👥 **Mentor(s):** TBD

📢 **Communication Channel:** Rocket.Chat Contributors Workspace  

💬 **Description:**  

This project focuses on refactoring the core Fuselage components to be built on top of the Tamagui library.
Once the Tamagui-based components are implemented, a comparative evaluation will be conducted against the current implementation, taking into account:

- Generated bundle size
- Runtime performance

From a visual standpoint, the components should not present any discrepancies, preserving the same appearance and behavior as the existing components.
Additionally, the Tamagui implementation must continue to use the existing design tokens, ensuring visual consistency and alignment with the current design system.

💪 **Desired Skills:**  
- Typescript

⏳ **Project Duration:**  
350 hours  

📈 **Difficulty:**  
Medium  
