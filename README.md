# 🕌 Qur’an Semantic Search (QA Retrieval)

This project is the second step in building a **faith-aware, responsible AI system** that understands Islamic teachings. It allows users to ask questions in natural language and receive the **most semantically relevant Qur’anic verse** in return.

---

## 📌 Why This Project?

In many NLP systems, keyword matching fails to capture the deeper meaning of user questions. When building an AI system for **Islamic knowledge**, it's important to:

- Retrieve **relevant and trustworthy** verses — even if users don't use exact wording
- Build the foundation for a **Muslim scholar chatbot**
- Encourage **hallucination-free, grounded AI** responses rooted in divine text

This project uses **semantic embeddings** to help the system "understand" the meaning of questions and link them to **Qur’anic concepts** accurately.

---

## 🧠 How It Works

1. We use [`sentence-transformers`](https://www.sbert.net) to generate semantic embeddings of Qur’anic verses.
2. When a user types a question, it is also embedded.
3. We calculate **cosine similarity** to find the **most relevant verse**.
4. The system returns the Surah, Ayah number, and verse text.

---

## 🌐 Example Use Case

> **User**: “What does Islam say about charity?”  
> **System**:  
> 📖 Surah: Al-Baqarah, Ayah: 267  
> 🕋 Verse: *"O you who have believed, spend from the good things which you have earned..."*

---

## 🏃 Getting Started (Google Colab)

### 1. Open the notebook in Google Colab

- <p align="left">
  <a href="https://colab.research.google.com/drive/1XW1LNExyzsQ1NYP6FjLCFk0DuBG1VwnA?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="150"/>
  </a>
</p>

### 2. Upload this file when prompted:
- <a href="https://drive.google.com/uc?export=download&id=1Eb3uiaYXRSUS7vJ2zGymxQ3mRMBcWJOq">
  <img src="https://img.shields.io/badge/📥_Download_Dataset-CSV-green?style=for-the-badge" alt="Download Dataset">
</a>

### 3. Run all cells and type your own question!

---

## 🧾 Dataset

We’re using a **mini Qur’an dataset** of ~25 carefully selected English-translated verses from various Surahs that cover:

- Worship & belief
- Morality
- Justice
- Charity
- Unity
- Patience
- Rights and duties

More verses can be added as needed in future phases.

---

## 🔮 What’s Next?

- 🔍 Add **Hadith corpus** to expand retrieval coverage
- 🗣️ Allow **multi-turn conversation** using chatbot interface
- 📜 Build a **faith-safe answer generator** grounded in retrieved verses
- 🧪 Integrate with `LangChain` or `RAG` pipelines for scalable QA

---

## 🔬 My AI Research Roadmap

This is the second step in building an explainable, ethical AI system for Islamic knowledge applications:
 
<a href="https://github.com/Akane-Asahi/Text-Classification-Islamic-vs-Non-Islamic-Content">
  <img src="https://img.shields.io/badge/🔎 Project_1-Text_Classification-blue?style=for-the-badge&logo=github" alt="GitHub Repository">
</a>    
👁️ Project 2: You Are here  
🧠 Project 3: Islamic intent classifier (Dialogue Act Tagging)  
🧩 Project 4: Build a rule-based + ML-based chatbot engine  
🤖 Project 5: Fine-tune LLMs on faith-aligned data (e.g., FaithDial)  

## 🤝 Author & Motivation
Built by Telot as part of a personal and academic journey to explore the intersection of:

📜 Faith-based knowledge  
🧠 Responsible AI  
🧪 Research in NLP and conversational agents  

This project is my first practical step toward a Muslim scholar chatbot that is rooted in verified sources and ethical design.

## 📬 Contact

Want to collaborate, mentor, or discuss faith-aware AI?
📧 Reach out at: heytelot@gmail.com
🌐 LinkedIn: 
<a href="https://www.linkedin.com/in/mosfaiulalam/">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-Mosfaiul%20Alam-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" width="250"/>
</a>

🪪 License
This project is open source under the MIT License.
