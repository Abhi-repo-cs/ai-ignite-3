
---

```markdown
# 🤖 Agentic AI Question Bank Generator & Auditor

### AI Ignite Hackacthon 2026 Project  
**Team Members:**  
• Abhishek  
• Shahid Asmar  
• Muralidharan  
• Hariharan  

---

## 🌟 Overview

This project is an **Agentic AI-powered platform** that automates the creation and evaluation of **outcome-aligned exam question banks**.  
Unlike simple AI text generators, this system uses **multi-stage autonomous reasoning** to:

✅ **Plan** the question strategy  
✅ **Generate** questions aligned to syllabus & course outcomes  
✅ **Audit** quality, clarity & Bloom level  
✅ **Auto-Repair** weak questions  
✅ **Detect duplicate risk**  
✅ **Provide analytics & exports**

The result is a **self-improving AI assessment assistant** designed for educators and universities.

---

## 🚀 Key Features

### 🤖 Multi-Agent AI Workflow
```

PLAN → GENERATE → AUDIT → REPAIR

```

### 🧠 Planning Agent
AI first creates a **strategy plan**:
- Bloom level mapping
- CO coverage plan
- Difficulty balance
- Risk controls
- Justifications

---

### ✍️ Generation Agent
AI generates questions:
- aligned to syllabus
- mapped to outcomes
- difficulty aware
- marks structured

---

### 🔍 Audit Agent
Each question is evaluated for:
- relevance
- clarity
- Bloom level
- difficulty
- improvement suggestions

---

### ♻ Repair Agent
Weak questions are:
- auto-rewritten
- improved
- re-audited
- stored as final version

---

### 📊 Analytics Dashboard
Includes:
- Bloom distribution
- difficulty distribution
- duplicate risk analysis
- quality metrics
- summary stats

---

### 📤 Export Support
Download question banks as  
✔ CSV  
✔ DOCX  
✔ PDF  

---

### ⭐ Feedback System
Users can:
- rate system
- leave comments
- view average rating

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| UI | Streamlit |
| AI Model | Groq LLaMA-3 |
| Processing | Python |
| NLP Similarity | TF-IDF + Cosine Similarity |
| Export | python-docx, reportlab |
| Storage | JSON Session Data |

---

## 🧩 Architecture

```

User → Input → Planning Agent
↓
Generation Agent
↓
Audit Agent
↓
Repair Agent
↓
Storage + Analytics + Export

````

---

## 🧠 Why Agentic AI?

Traditional LLM apps are **one-shot generators**.

This system is different because it:

✔ reasons  
✔ decides  
✔ acts  
✔ evaluates  
✔ self-corrects  
✔ logs decisions  

This demonstrates **autonomous intelligence** — a key goal of modern AI.

---

## 📌 Use-Cases

🎓 Universities  
🧪 Accreditation bodies  
📘 Teachers  
🏫 Ed-Tech Platforms  

---

## 🏁 How To Run

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
````

### 2️⃣ Add API Key

Create:

```
.streamlit/secrets.toml
```

Include:

```
GROQ_API_KEY = "your_key_here"
```

### 3️⃣ Run App

```bash
streamlit run app.py
```

---

## 📊 Evaluation Metrics

* Bloom level balance
* Outcome alignment
* Duplicate risk score
* Difficulty variation
* Clarity audit
* User satisfaction rating

---

## 🔮 Future Enhancements

* Multi-teacher collaboration
* Secure login/auth
* Persistent DB storage
* Question paper generator
* Adaptive weighting
* Plagiarism screening
* LMS integration

---

## 🏆 Why This Project Matters

Assessment quality directly impacts learning outcomes.

This system:

✔ saves time
✔ ensures fairness
✔ standardizes evaluation
✔ supports accreditation
✔ enables data-driven teaching

---

## ❤️ Acknowledgements

Built with
✨ Passion
✨ Purpose
✨ Innovation

for **IgniteHack 2026**

---

## 📧 Contact

If you'd like to collaborate or extend this project,
reach out to the team anytime 🚀

```

---

#PROJECT DOCUMENTATION : https://docs.google.com/document/d/1-Vi6NPiz1Fl_ytqhp-_riOS9c0J7qh2KPy2L_gU0AYg/edit?usp=sharing