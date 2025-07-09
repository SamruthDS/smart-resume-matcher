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
├── requirements.txt # All dependencies
├── README.md # Project overview
├── .gitignore # Files to ignore in Git
└── LICENSE # License info (MIT, etc.)


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
## ☁️ How to Run on Google Colab:

You can also run this project directly in Google Colaboratory:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SamruthVadada/smart-resume-matcher/blob/main/Smart_Resume_Matcher.ipynb)

**[Click here to open in Google Colab!](https://colab.research.google.com/github/SamruthVadada/smart-resume-matcher/blob/main/Smart_Resume_Matcher.ipynb)**


### 💻 Option 2: Run Locally

1. Clone the repository  
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

2.Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install dependencies
pip install -r requirements.txt

4.Launch the app
Run the notebook in Jupyter or Colab, or extract code into app.py and run:

python app.py

🌐 Live Demo
🔗 **Access the Live Application Here:** [https://huggingface.co/spaces/SamruthVadada/smart-resume-matcher](https://huggingface.co/spaces/SamruthVadada/smart-resume-matcher)

🙋‍♂️ Developer
Samruth Vadada
📫 vadadasamruth@gmail.com
🔗 [GitHub](https://github.com/SamruthVadada/smart-resume-matcher)

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.


