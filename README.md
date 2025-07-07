# MeetingMate – A GenAI-Powered Smart Meeting Companion

Welcome to the capstone project of the **Generative AI Intensive Course**!

**MeetingMate** is your intelligent meeting assistant that transforms chaotic discussions into structured, insightful outputs — all from a simple audio upload.

---

## 🧠 The Problem

Tired of long, unproductive meetings that leave you wondering what was actually decided?  
We’ve all been there — unstructured conversations, scattered notes, and forgotten action items. It’s easy to lose track of key points, next steps, or even *who said what*.

---

## ✅ The Solution: **MeetingMate**

Just upload your meeting audio, and let MeetingMate handle the rest. It:
- 🎯 Summarizes your conversation
- 💬 Enables interactive Q&A trained on your meeting content
- 📊 Generates a clean, presentation-ready slide deck

Powered by cutting-edge tools like **OpenAI Whisper**, **Google Gemini**, **ChromaDB**, and **Python automation**, MeetingMate converts your conversations into actionable insights — instantly.

---

## ✨ Key Features Demonstrated

| Feature                                | Description |
|----------------------------------------|-------------|
| 🎧 **Audio Transcription**             | Converts meeting audio into text using **OpenAI Whisper** |
| 🧾 **Document Understanding**          | Generates structured slides using **python-pptx** |
| 🧠 **Prompt Engineering**              | Crafts role-based prompts for summaries and insights |
| 📦 **Structured Output (JSON)**        | Uses `google.generativeai.types` for clean and parsable model responses |
| 🧪 **GenAI Evaluation**                | Rubric-based evaluation of generated summaries using Gemini |
| 🔁 **Embeddings & RAG**                | Stores past meetings in **ChromaDB** and retrieves them based on semantic similarity |

---

## 🔄 What We Built

MeetingMate takes in a meeting audio file and walks through this **end-to-end pipeline**:

1. **Transcription**  
   → Converts audio to text using **Whisper**  
2. **Summarization**  
   → Summarizes the transcript with the **Gemini API**  
3. **Slide Generation**  
   → Creates a PowerPoint deck of key takeaways using **python-pptx**  
4. **Retrieval**  
   → Uses **ChromaDB** to pull in context from previous meetings  
5. **Evaluation**  
   → Grades the outputs via **rubric-based GenAI evaluation**

---

## 🧰 Technologies Used

- 🗣️ **[OpenAI Whisper](https://github.com/openai/whisper)** – Speech-to-text transcription
- 🧠 **[Google Gemini API](https://ai.google.dev/)** – Summarization & text generation
- 📊 **[python-pptx](https://python-pptx.readthedocs.io/)** – Automated slide deck generation
- 🔍 **[ChromaDB](https://www.trychroma.com/)** – Vector database for semantic search and retrieval

---

## 📌 Future Ideas

- Speaker diarization to track who said what
- Custom Q&A chatbot interface
- Real-time transcription and summarization

---

## 📄 License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

Built as part of the **Generative AI Intensive Capstone** — thanks to the community and instructors for support and inspiration.

---
