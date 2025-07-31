# 🧠 Resume–Job Description Matcher

This project uses **semantic similarity** to match resumes with job descriptions using NLP and deep learning. It helps rank job listings by how well they fit a given resume.

---

## ✨ Features

- Sentence-level semantic matching using transformer-based embeddings
- Computes similarity scores between resumes and job descriptions
- Ranks job matches for each resume
- Visualizes results using matplotlib/seaborn
- Works with custom datasets (CSV/text files)

---

## 🛠 Tech Stack

- Python 3.11+
- [Sentence Transformers](https://www.sbert.net/)
- Pandas, NumPy
- Matplotlib, Seaborn
- PyTorch (via Transformers backend)

---

## 📁 Project Structure

```text
resume_job_matcher/
├── Resume/
│   ├── resumes.csv
│   └── jobs.csv
├── HR_Screening.ipynb
├── README.md
└── requirements.txt
```


---

#
---

## 📦 Installation

1. Clone the repository:
```bash
   git clone https://github.com/syedaraheen/Resume_Job_Matcher.git
   cd resume_job_matcher
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
```
📊 Usage
1. Prepare your dataset

This project uses the **Resume and Job Description Matching** dataset available on Kaggle:
## 📂 Dataset  
🔗 **Resume and Job Description Dataset – by Pranav Venugopal**  
[https://www.kaggle.com/datasets/pranavvenugo/resume-and-job-description](https://www.kaggle.com/datasets/pranavvenugo/resume-and-job-description)


Please download the dataset manually from the link above and place it in the `Resume/` directory:

## 🚀 How to Use

1. Open the Jupyter Notebook:  
   - `HR_Screening.ipynb`

2. Run the notebook cells step-by-step to:
   - Load resume and job datasets  
   - Compute similarity scores  
   - Rank job descriptions per resume  
   - Visualize the results  

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 👨‍💻 Author

**Raheen Bukhari**  
📫 Email: raheenbukhari.01@gmail.com  
🔗 LinkedIn: [https://www.linkedin.com/in/syeda-raheen-bukhari-5366aa2b2/](https://www.linkedin.com/in/syeda-raheen-bukhari-5366aa2b2/)
