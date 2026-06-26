# 🩺 HealthLens

**AI-Powered Blood Test Report Interpretation System and Medical Report Analyzer**........//////////

## 📌 Overview

HealthLens is an AI-driven application designed to automate the extraction, interpretation, and summarization of blood test reports. The system leverages **OCR, Large Language Models (LLMs)**, and an **agent-based architecture** to convert complex medical data into clear, patient-friendly insights.

Built with scalability and responsible AI principles in mind, this project demonstrates how **multi-agent AI systems** can be applied to real-world healthcare use cases.

---

## 🎯 Problem Statement

Blood test reports are often difficult for non-medical users to understand due to complex terminology and numerical reference ranges. Manual interpretation is time-consuming and requires medical expertise.

This project aims to:

* **Automate** blood report analysis.
* Improve healthcare data **accessibility**.
* Provide **simplified**, explainable insights for patients and students.

---

## 🚀 Key Features

* 📄 **Automated OCR Extraction** from uploaded blood test reports.
* 🤖 **Agent-Based Architecture** using CrewAI.
* 🧠 **LLM-Powered Medical Interpretation** with reference range mapping.
* 📝 **Patient-Friendly Summaries** generated via prompt engineering.
* 🎛 **Streamlit Web Interface** for easy report upload and analysis.
* 🔄 **Modular & Scalable Design** for future diagnostic extensions.
* 🔐 **Responsible AI Practices** with no sensitive data retention.

---

## 🏗 System Architecture

The system is built using a **multi-agent pipeline**, where each agent performs a specialized task:

1. **OCR Parser Agent**

   * Extracts text from uploaded blood reports using Tesseract OCR.
     
2. **Health Data Interpreter Agent**

   * Identifies medical parameters.
   * Maps values to standard reference ranges.
   * Generates contextual medical insights using LLMs.
     
3. **Summary Generator Agent**

   * Converts technical results into simplified, patient-friendly explanations.

Agents are orchestrated sequentially using **CrewAI** to ensure clean data flow and modular execution.

---

## 🛠 Tech Stack

### 🔹 AI & NLP

* CrewAI (Agent orchestration)
* Hugging Face Transformers
* Prompt Engineering & Caching

### 🔹 OCR

* Tesseract OCR

### 🔹 Backend / Logic

* Python
* Modular agent workflows
* Structured data passing between agents

### 🔹 Frontend

* Streamlit (Interactive web UI)

---

## 📂 Project Structure

```
medical-report-analyzer/
│
├── agents/
│   ├── ocr_parser.py
│   ├── health_interpreter.py
│   └── summary_generator.py
│
├── app.py                  # Streamlit application
├── requirements.txt
├── README.md
└── utils/
    ├── prompts.py
    └── helpers.py
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ahmasmibhanu/HealthLens.git
cd HealthLens
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 🧪 Usage

1. Upload a **blood test report** (PDF or image).
2. OCR extracts the report text.
3. AI agents analyze medical parameters.
4. A **simplified**, **patient-friendly summary** is generated.
5. Results are displayed in real-time on the UI.

---

## 📊 Impact & Results

* Reduced manual effort in interpreting blood reports.
* Improved healthcare data accessibility for non-technical users.
* Achieved accurate extraction across diverse report formats.
* Received positive usability feedback from medical students and early testers.
* Demonstrated the feasibility of agent-based AI systems in healthcare.

---

## 🔮 Future Enhancements

* Backend API using FastAPI.
* Database integration for report history.
* Explainability scores and confidence metrics.
* Authentication and role-based access.
* Support for additional diagnostics (X-ray, MRI reports).
* Deployment using Docker and cloud platforms.

---

## ⚠️ Disclaimer

This tool is intended for **educational and informational purposes only**.
It does **not** provide medical diagnosis or treatment advice. Always consult a qualified healthcare professional for medical decisions.

---

## 👨‍💻 Author

**@ahmasmibhanu**
**~AI / Full Stack / Software Engineering Enthusiast**

---

## ⭐ Acknowledgements

* CrewAI
* Hugging Face
* Streamlit
* Open-source OCR and NLP communities

---

### ⭐ If you find this project useful, consider starring the repository!

---
