# 🎤 Conversational AI Pipeline (Speech‑to‑Text → Cerebras API → Text‑to‑Speech)

This project is a simple Python-based conversational AI system that listens to the user’s voice, converts it into text, sends the text to the **Cerebras LLM API**, receives a generated response, and finally converts that response back into speech.

---

# __*Diana*__

## 🚀 Project Overview

The goal of this project is to create a lightweight voice assistant using three main components:

### 1. Speech‑to‑Text (STT)
The system records audio from the user’s microphone and converts it into text using any STT engine (e.g., `speech_recognition`, Whisper, etc.).

### 2. Cerebras API (LLM Processing)
The recognized text is sent to the **Cerebras** large language model API.  
The model generates a natural-language response based on the user’s input.

### 3. Text‑to‑Speech (TTS)
The generated response is converted back into speech using a TTS engine (e.g., `gTTS`, `pyttsx3`, or another service).

---

## 🧠 How It Works (Flow)

1. User speaks into the microphone  
2. Audio is captured and converted to text  
3. Text is sent to Cerebras API  
4. Cerebras returns a generated response  
5. Response text is converted to speech  
6. Audio is played back to the user  

This creates a simple, continuous voice-based interaction loop.

---

## 📦 Use Cases

- Voice assistants  
- Smart home prototypes  
- Interactive chatbots  
- Hands‑free AI tools  
- Educational or accessibility applications  

---

## 🛠️ Tech Stack

- **Python**
- **Speech Recognition** (STT)
- **Cerebras LLM API**
- **Text‑to‑Speech Engine** (TTS)
- **Audio playback library**

---

## 📁 Example Project Structure

