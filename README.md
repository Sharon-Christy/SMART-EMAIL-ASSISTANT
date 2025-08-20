📧 EMAIL-ASSISTANT-ASSISTANT
Transforming Emails, Accelerating Productivity Daily

Last Commit Java Languages

🛠 Built with the tools and technologies
JSON Markdown Spring npm JavaScript React XML Vite ESLint Axios Bootstrap

📚 Table of Contents
Overview
Getting Started
Prerequisites
Installation, Usage & Testing
🧠 Overview
Email-Assistant-VK is a versatile developer toolkit that integrates AI-driven communication, research, and transcription functionalities into your applications.

🔑 Key Features
🧩 Modular Architecture: Built with Spring Boot and React for easy customization.
⚡ Real-time AI: Gemini-powered smart email suggestions and research responses.
🧠 AI Chat + Q&A: Streamlines writing and learning workflows.
🎯 Developer Friendly: Well-structured source code and config setup.
🎙️ Audio Transcription: Converts speech to text using Whisper or DeepSeek.
🔗 CORS Supported: Smooth frontend-backend communication.
🚀 Getting Started
🧰 Prerequisites
Ensure the following are installed on your system:

Java 17+
Maven
Node.js & npm
Gemini API Key
⚙️ Installation, Usage & Testing
1. Clone the Repository
git clone https://github.com/vigneshkumar-26/Email-Assistant-VK
cd Email-Assistant-VK

2. Set up the Spring Boot Backend
cd audio-transcribe
mvn install

3. Add Gemini API Key
# Edit this file:
# src/main/resources/application.properties
spring.ai.gemini.api-key=YOUR_API_KEY

4. Run Backend
mvn spring-boot:run

5. Set up Frontend (in a new terminal)
cd ../audio-transcribe-frontend
npm install
npm run dev

6. Run Tests

Backend Tests
cd ../audio-transcribe
mvn test

Frontend Tests
cd ../audio-transcribe-frontend
npm test
