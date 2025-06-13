# AI-Powered-Gmail-Assistant-Chrome-Extension

A smart Gmail assistant built using **Spring Boot** and integrated with the **Gemini API**, designed to generate intelligent, context-aware email replies directly inside the Gmail interface through a custom Chrome Extension.

---

## 🚀 Features

- 🧠 **AI Reply Suggestions** using Gemini API
- 🔌 **Chrome Extension** that integrates natively into Gmail
- 🔒 **Spring Boot Backend** for secure and scalable API handling
- 💡 Real-time email content capture and intelligent response generation

---

## 🛠️ Tech Stack

| Layer        | Technology          |
|--------------|---------------------|
| Frontend     | Chrome Extension (JavaScript, HTML, CSS) |
| Backend      | Spring Boot (Java)  |
| AI Service   | Gemini API (by Google) |
| Deployment   | Localhost (for now) |

---

## 📦 Setup Instructions

### 1. Clone the Repository

### 2. Backend Setup (Spring Boot)
Ensure you have Java 17+ and Maven installed.

Add your Gemini API key in application.properties:
gemini.api.url=YOUR_GEMINI_URL
gemini.api.key=YOUR_GEMINI_KEY

Run the Spring Boot application
By default, the server runs at: http://localhost:8080

###3. Chrome Extension Setup
Open Chrome and go to: chrome://extensions/

Enable Developer Mode

Click Load Unpacked

Select the chrome-extension folder from this project

The extension should now be active in Gmail

---

## 🧪 How It Works
The Chrome Extension captures the content of open emails in Gmail.

It sends that content to the Spring Boot backend.

The backend uses the Gemini API to generate a relevant smart reply.

The suggestion is returned and shown directly in Gmail for quick use.

---

## 🙋‍♂️ Author
SUBRATH MODI JAIN
🔗 LinkedIn - https://www.linkedin.com/in/subrath-modi-jain-444680284/
📧 subrathmodi@gmail.com
