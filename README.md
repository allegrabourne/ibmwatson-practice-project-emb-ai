# 🧠 Embedded AI Practice Project

This project is a fork of the official [IBM Watson Embedded AI Practice Project](https://github.com/ibm-developer-skills-network/zzrjt-practice-project-emb-ai), originally designed by IBM as part of their Developer Skills Network. It serves as a hands-on template for understanding how **AI models can be deployed and run in lightweight or embedded environments**, such as IoT devices or edge hardware.

---

## 🎯 Project Goals

This fork was created to:

- Learn the basics of **embedding AI inference logic into web-based applications**
- Experiment with **lightweight AI model integration**
- Understand how front-end and back-end layers communicate to run AI predictions
- Extend the template into a custom application (e.g., sentiment analysis, object detection, keyword spotting)

---

## 🔧 What's Included

- `static/mywebscript.js` – Handles front-end interaction with the server
- `templates/index.html` – A Bootstrap-styled HTML page for user input and result display
- `server.py` – Python backend that handles incoming requests and returns AI model predictions
- `Project.md` – (this file) describes the fork and my personal goals or changes

---

## 🚀 How It Works

1. User enters input on the web interface.
2. JavaScript sends an asynchronous `GET` request to the backend with the input data.
3. The Python backend performs sentiment/emotion detection (or other inference) and returns a text response.
4. The result is dynamically displayed on the same page.

---

📜 License
This project is based on IBM's public learning resources and is used here for educational and developmental purposes.


