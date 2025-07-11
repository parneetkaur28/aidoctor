# 🧠 AI Doctor with Vision and Voice 🤖🩺

An intelligent generative AI application that acts like a virtual doctor — accepting **images of physical issues** (like injuries or skin conditions) and **voice-based questions** to generate medical-like advice using state-of-the-art multimodal LLMs. The application is powered by **Gradio**, **Groq’s LLaMA 4**, and **gTTS**.

---

## 🚀 Features

- 📸 **Image Analysis**: Upload an image of your injury, scar, or visible medical issue.
- 🎙️ **Voice Input**: Ask your health-related question using your voice.
- 💬 **Multimodal Response Generation**: Combines your image and question to generate a response using `meta-llama/llama-4-scout-17b-16e-instruct` via **Groq API**.
- 🔊 **AI Doctor Speaks**: The generated answer is converted to **spoken audio** using **gTTS (Google Text-to-Speech)**.
- 🌐 **Gradio UI**: Simple, intuitive web interface to interact with the AI doctor.

---

## 🛠️ Tech Stack

| Component     | Description                                           |
|---------------|-------------------------------------------------------|
| **Gradio**    | UI to record voice, upload image, and show responses  |
| **Groq**      | Fast inference of LLaMA 4 model for answer generation |
| **gTTS**      | Converts AI response into audio for playback          |
| **Python**    | Core logic and orchestration                          |

---

## 📦 Installation

-Clone the repository or download as zip and create a virtual environment to install packages from piplock file for exact versions.
-Set up the environment variables- Groq API key and ElevenLabs API key(if used).
-Verify the LLM model being used is not depricated.

Then use -
## python gradio_app.py
