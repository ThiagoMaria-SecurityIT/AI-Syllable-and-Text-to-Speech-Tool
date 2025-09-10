# AI Syllable and Text-to-Speech Tool

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Framework-Gradio-orange" alt="Gradio Framework">
  <img src="https://img.shields.io/badge/AI_Model-Coqui_TTS-green" alt="AI Model">
  <img src="https://img.shields.io/badge/Built_with-Manus_AI-9cf" alt="Built with Manus AI">
</p>

Welcome! This project is an educational tool designed to show how modern AI and classic programming techniques can be combined to create a useful application. It started as a simple desktop app and evolved into a powerful, web-based AI tool hosted on Hugging Face.  

<img width="1899" height="899" alt="image" src="https://github.com/user-attachments/assets/0b1648c3-d426-414e-bde3-93fe9a5700c4" />  


The application has two main functions:
1.  **A Syllable Splitter:** It takes an English word, splits it into its phonetic syllables, and lets you hear them spoken.
2.  **A Direct Text-to-Speech (TTS ) Tool:** It can take any English text and convert it into high-quality speech using an AI model.

This repository is perfect for learners interested in Python, GUI development, and how to use AI models in a practical project.

---

### Index

1.  [Live Demo](#live-demo)
2.  [Features](#features)
3.  [How It Works: The Technology](#how-it-works-the-technology)
4.  [How to Run This Project](#how-to-run-this-project)
5.  [Project Evolution: From Desktop App to AI Web App](#project-evolution-from-desktop-app-to-ai-web-app)
6.  [AI Transparency: A Note on Collaboration](#ai-transparency-a-note-on-collaboration)

---

### Live Demo

You can try out the final, web-based version of this application live on Hugging Face Spaces:

**[AI Syllable and Text-to-Speech Tool Live](https://huggingface.co/spaces/ThiSecur/tts3-project )**

---

### Features

*   **Two Tools in One:** A dedicated tool for syllable analysis and a general-purpose Text-to-Speech engine.
*   **AI-Powered Speech:** Uses the high-quality Coqui TTS model for natural and clear audio generation.
*   **Interactive Interface:** Built with Gradio, the interface is user-friendly and allows for editing the syllabified text before generating audio.
*   **Web-Based and Accessible:** As a Hugging Face Space, the tool requires no installation and can be used by anyone with a web browser.

---

### How It Works: The Technology

This project combines several key libraries to achieve its functionality:

*   **Gradio:** Used to build and host the interactive web interface. It's a fantastic Python library for creating demos for machine learning models.
*   **Pyphen:** A library for splitting words into syllables. It uses dictionary-based rules to ensure phonetic accuracy.
*   **Coqui TTS (`🐸 TTS`):** A powerful, open-source library for Text-to-Speech. We use one of its pre-trained English models to convert text into spoken audio.
*   **PyTorch:** The underlying machine learning framework that runs the Coqui TTS model.

The application is structured with a clear, two-step workflow for the syllable tool, making it easy to see the intermediate result before hearing the final audio.

---

### How to Run This Project

Since the final version is a web app, the easiest way to use it is via the [Live Demo](#live-demo) link.

However, if you wish to run the project on your own computer to experiment with the code, Hugging Face makes this very simple:

1.  Go to the project's **[AI Syllable and Text-to-Speech Tool Live](https://huggingface.co/spaces/ThiSecur/tts3-project )**.  
2.  Click on the **three dots ( • • • )** menu icon at the top-right of the page.
3.  Select **"Run locally"**.
4.  You can follow the instructions to run it locally on your machine. This process handles the dependencies and setup for you.

---

### Project Evolution: From Desktop App to AI Web App

This project didn't start as a web app. Its journey is a great lesson in software development:

1.  **Initial Goal:** Create a simple Python script to split syllables.
2.  **Desktop App:** We first built a desktop application using `Tkinter` and a basic, offline TTS engine (`pyttsx3`).
3.  **The Limitation:** We discovered that the basic Windows TTS voices struggled to pronounce isolated syllables correctly (e.g., reading "cor" as "C-O-R").
 - Check the desktop version here: [Syllable-Splitter-and-Speaker](https://github.com/ThiagoMaria-SecurityIT/Syllable-Splitter-and-Speaker)
4.  **The Pivot to AI:** To solve this, we decided to use a modern AI-powered TTS model. We chose to host it on Hugging Face to avoid requiring users to have powerful hardware.
5.  **Final Version:** The project evolved into a full-fledged Gradio web application, which is more powerful, accessible, and provides much higher-quality results than the original desktop app.

This evolution shows how encountering limitations can lead to better, more modern solutions.

---

### AI Transparency: A Note on Collaboration

This project was developed collaboratively between a human developer and **Manus**, an AI agent from the Manus team.


