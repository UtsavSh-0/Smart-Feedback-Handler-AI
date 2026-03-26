# 🤖 Smart Feedback Handler AI

An intelligent AI-powered workflow that processes user feedback in real time, detects sentiment, and takes automated actions to improve user experience and team response time.

---

## 🚀 Features

- 🔍 **AI Feedback Analysis** – Automatically analyzes user feedback  
- ⚠️ **Negative Feedback Handling**
  - Sends alerts to team via Slack  
  - Sends apology message to user  
- 😊 **Positive Feedback Management**
  - Stores compliments in database  
- 🧠 **AI Decision Making** – Smart sentiment classification  
- 🔄 **Fully Automated Workflow**

---

## 🏗️ Workflow

```mermaid
graph TD
A[User Feedback] --> B[AI Agent]
B --> C{Sentiment?}
C -->|Negative| D[Send Slack Alert]
C -->|Negative| E[Send Apology to User]
C -->|Positive| F[Store in Database]

<img width="1118" height="415" alt="image" src="https://github.com/user-attachments/assets/ea9ccc31-59da-4059-8a1a-c3781c870a78" />
<img width="627" height="558" alt="image" src="https://github.com/user-attachments/assets/9c86c4a4-521b-4fa6-9705-44a5a359ba68" />


