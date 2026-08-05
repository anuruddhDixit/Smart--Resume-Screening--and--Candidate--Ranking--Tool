# Smart Resume Screening and Candidate Ranking Tool

An AI-powered application that automates resume screening and ranks candidates based on their relevance to a given job description using **Natural Language Processing (NLP)** and **Machine Learning (ML)**.

---

## Overview

Recruiters often spend significant time manually reviewing resumes. This project streamlines the hiring process by automatically analyzing resumes, extracting relevant information, comparing candidate profiles with job requirements, and ranking applicants according to their suitability.

The system leverages NLP techniques for text preprocessing and feature extraction, along with machine learning-based similarity scoring to provide accurate candidate rankings.

---

## Features

* Resume parsing from PDF and DOCX files
* Job description analysis
* NLP-based text preprocessing
* Keyword and skill extraction
* Resume-job matching using TF-IDF and Cosine Similarity
* Candidate ranking based on match score
* Interactive visualizations
* Fast and automated screening process

---

## Tech Stack

| Category             | Technologies              |
| -------------------- | ------------------------- |
| Programming Language | Python                    |
| Data Processing      | Pandas, NumPy             |
| Machine Learning     | Scikit-learn              |
| NLP                  | NLTK, spaCy               |
| Similarity           | TF-IDF, Cosine Similarity |
| Visualization        | Matplotlib, Plotly        |
| Web Framework        | Streamlit                 |
| Development          | Jupyter Notebook          |

---

## Project Structure

```text
Smart-Resume-Screening/
│
├── data/
│   ├── resumes/
│   ├── job_description.txt
│
├── models/
│
├── notebooks/
│   └── resume-screening-using-ml-and-nlp.ipynb
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Smart-Resume-Screening.git
```

Move into the project folder:

```bash
cd Smart-Resume-Screening
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## Workflow

1. Upload resumes (PDF/DOCX)
2. Upload or enter the job description
3. Extract text from resumes
4. Preprocess text using NLP
5. Generate TF-IDF vectors
6. Calculate Cosine Similarity
7. Assign match scores
8. Rank candidates
9. Display ranked results and visualizations

---

## Project Objective

To build an intelligent recruitment assistant that automates resume screening, identifies the most relevant candidates, and improves hiring efficiency using AI, NLP, and Machine Learning.

---

## Future Improvements

* Deep Learning-based resume matching
* Named Entity Recognition (NER) for better skill extraction
* Semantic matching using Sentence Transformers/BERT
* Resume recommendation system
* Multi-language resume support
* Recruiter dashboard with analytics

---

## Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License.

---

