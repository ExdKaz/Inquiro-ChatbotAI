# 🤖 Inquiro — AI Chatbot using Angular + Spring Boot + OpenAI

Inquiro is a full-stack chatbot built with Angular 17 and Spring Boot. It connects to the OpenAI API (ChatGPT) and provides a clean, responsive chat interface. Easily customizable for your own use cases like customer support, personal assistants, or internal Q&A tools.

---

## 🔧 Tech Stack

| Frontend      | Backend       | AI Engine      |
|---------------|---------------|----------------|
| Angular 17.3  | Spring Boot 3 | OpenAI GPT-3.5 / 4 |
| PrimeNG UI    | REST APIs     | Chat Completions API |
| TypeScript    | Java 17+      | JSON over HTTP |

---

## 🚀 Features

- Real-time chat interface
- OpenAI-powered responses (GPT-3.5 or GPT-4)
- Modern UI with message bubbles
- Angular service + Spring REST integration
- Chat history stored in memory (can be extended to DB)
- Clean architecture: frontend and backend in separate folders
- Ready for deployment or extension

---

## 🖥️ Project Structure

```bash
chatbot-app/
├── frontend/     # Angular 17 app
│   ├── src/
│   ├── angular.json
│   └── ...
├── backend/      # Spring Boot app
│   ├── src/
│   ├── pom.xml
│   └── ...
└── README.md
