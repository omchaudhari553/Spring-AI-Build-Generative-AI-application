<div align="center">

# 🤖 Spring-AI-Build-Generative-AI-Application

### Generative AI Application with Spring AI

A backend application built using Spring Boot and Spring AI to integrate Large Language Models into Java applications. The project demonstrates prompt engineering, AI chat integration, structured output parsing, and retrieval-based AI workflows.

<br/>

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-1.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?style=for-the-badge&logo=openai&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

</div>

---

## 📌 Project Overview

This project demonstrates how to build generative AI applications in Java using :contentReference[oaicite:1]{index=1} and :contentReference[oaicite:2]{index=2}. It integrates LLM APIs to create AI-powered services such as chat completion, prompt-based question answering, and document-aware responses.

---

## ✨ Features

| Module | Description |
|---|---|
| 💬 AI Chat | Conversational API integration with LLM |
| 🧠 Prompt Engineering | Dynamic prompts for contextual responses |
| 📄 Structured Output | JSON/DTO response parsing |
| 🔍 RAG Demo | Retrieval Augmented Generation using external documents |
| 🔗 LLM API Integration | Connects to OpenAI models |
| 📖 Swagger UI | API testing and documentation |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Backend | Java 17, :contentReference[oaicite:3]{index=3} |
| AI | :contentReference[oaicite:4]{index=4} |
| Model Provider | :contentReference[oaicite:5]{index=5} GPT |
| Build Tool | Maven |
| Documentation | Swagger/OpenAPI |
| Testing | JUnit 5 |

---

## 📁 Project Structure

```text
Spring-AI-Build-Generative-AI-application/
├── src/main/java/com/example/
│   ├── controller/
│   │   └── AIController.java
│   ├── service/
│   │   └── AIService.java
│   ├── config/
│   │   └── AIConfig.java
│   └── dto/
├── src/main/resources/
│   └── application.properties
└── pom.xml
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/Spring-AI-Build-Generative-AI-application.git
cd Spring-AI-Build-Generative-AI-application
```

### Configure API Key

Add your API key in `application.properties`:

```properties
spring.ai.openai.api-key=YOUR_API_KEY
```

### Run Application

```bash
mvn clean install
mvn spring-boot:run
```

Application runs at:

```text
http://localhost:8080
```

Swagger UI:

```text
http://localhost:8080/swagger-ui.html
```

---

## 🌐 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/api/ai/chat` | Chat with AI |
| `POST` | `/api/ai/prompt` | Generate response from prompt |
| `POST` | `/api/ai/rag` | RAG-based response |
| `GET` | `/api/ai/health` | Service health check |

---

## 📌 Learning Highlights

- Integrated LLM APIs into Java backend  
- Implemented prompt engineering techniques  
- Built structured response parsing  
- Created RAG-based document querying  
- Explored enterprise AI integration using Spring ecosystem  

---

## 👨‍💻 Author

Developed by **Om Chaudhari** to learn and demonstrate Generative AI application development using Java and Spring AI.

---
