---
title: Smart Resume Matcher
emoji: 🧠📄
colorFrom: blue
colorTo: purple
sdk: gradio
sdk_version: "4.36.1" # A recent stable Gradio version
app_file: Smart_Resume_Matcher.ipynb # This tells Hugging Face to run your notebook
pinned: false
---

# Smart Resume Matcher – AI Tool for Job Seekers & Recruiters 🧠📄

An AI-powered resume matching tool built using **Gradio**, **Python**, and **NLP** techniques, designed to help **recruiters** find top candidates and assist **job seekers** in evaluating their resume-fit for a job.

---

## 🚀 Features

🔹 **Recruiter Mode**
Upload multiple resumes and match them against a job description to get a ranked list of top candidates.
Export detailed match scores as a downloadable CSV.

🔹 **Job Seeker Mode**
Upload or paste your resume, enter a job description, and instantly receive a personalized match score.

🔹 **Custom + Predefined Job Descriptions**
Use your own JD or select from built-in roles like *Data Scientist*, *Software Engineer*, *UX Designer*, etc.

🔹 **Intelligent Resume Validation**
Detects and filters out non-resume files (like certificates or blank documents).

🔹 **Powerful Text Matching**
Uses **TF-IDF** and **Cosine Similarity** for accurate content comparison.

🔹 **User-Friendly Interface**
Built with **Gradio** for a clean, interactive experience.

---

## 📁 Project Structure

📦 Smart Resume Matcher/
├── Smart_Resume_Matcher.ipynb # Main Notebook (Gradio App)
├── requirements.txt           # All Python dependencies
├── README.md                  # Project overview and documentation
├── .gitignore                 # Files to ignore in Git
└── LICENSE                    # License information (MIT, etc.)

---

## 🛠️ Technologies Used

- Python
- Gradio
- Scikit-learn
- PyMuPDF (fitz)
- python-docx
- pandas & numpy
- re, os, tempfile

---

## ✅ How to Run

### ▶️ Option 1: Run in Google Colab

You can run this project directly in Google Colaboratory. This is the quickest way to get started without any local setup.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SamruthVadada/smart-resume-matcher/blob/main/Smart_Resume_Matcher.ipynb)

**[Click here to open in Google Colab!](https://colab.research.google.com/github/SamruthVadada/smart-resume-matcher/blob/main/Smart_Resume_Matcher.ipynb)**


### 💻 Option 2: Run Locally

To set up and run the project on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SamruthVadada/smart-resume-matcher.git](https://github.com/SamruthVadada/smart-resume-matcher.git)
    cd smart-resume-matcher
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    # .\venv\Scripts\activate
    # On macOS/Linux:
    # source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch the Gradio app:**
    ```bash
    gradio Smart_Resume_Matcher.ipynb
    ```
    *(If `gradio` command is not found, try `python -m gradio Smart_Resume_Matcher.ipynb`)*

    This will launch the Gradio interface in your local web browser, typically at `http://127.0.0.1:7860`.

---

## 🌐 Live Demo

Experience the Smart Resume Matcher in action right now on Hugging Face Spaces!

🔗 **Access the Live Application Here:** [https://huggingface.co/spaces/SamruthVadada/smart-resume-matcher](https://huggingface.co/spaces/SamruthVadada/smart-resume-matcher)

---

## 🙋‍♂️ Developer

**Samruth Vadada**
* **Email:** vadadasamruth@gmail.com
* **GitHub:** [https://github.com/SamruthVadada/smart-resume-matcher](https://github.com/SamruthVadada/smart-resume-matcher)

---

## 📄 License

This project is open-source and distributed under the **MIT License**. See the `LICENSE` file in the repository for full details.
