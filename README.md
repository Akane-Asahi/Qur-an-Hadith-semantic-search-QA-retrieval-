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

<p align="left">
  <a href="https://colab.research.google.com/drive/1XW1LNExyzsQ1NYP6FjLCFk0DuBG1VwnA?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="150"/>
  </a>
</p>

### 2. Upload this file when prompted:
- `mini_quran_dataset.csv` – [Download it here](sandbox:/mnt/data/mini_quran_dataset.csv)

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

## 📬 Contact

Built by [Your Name] as part of a journey to responsibly integrate AI with Islamic ethics and scholarship.

📧 your_email@example.com  
🔗 LinkedIn: [your-linkedin-profile]

---

## 🪪 License

This project is open-sourced under the [MIT License](LICENSE).
