# 🧮 Linear Algebra for Data Science — A Hands-On Handbook with Python

Welcome to **Linear Algebra for Data Science**, a practical, example-driven guide designed for data-science students and professionals.  
Each concept in linear algebra is explained using **intuitive math, visual demos, and one consistent NLP example** — a small text corpus that ties all notebooks together.

---

## 📚 Project Overview

Linear algebra is the mathematical foundation behind machine learning, NLP, computer vision, and deep learning.  
This repository turns abstract concepts into **interactive Jupyter notebooks** with **Python code, plots, and text-based data**.

The project follows a single **running NLP example**:
> A small corpus of text reviews is converted into a **term-document matrix**, and every linear-algebra topic (vectors, subspaces, projections, eigenvectors, SVD, etc.) is demonstrated using this dataset.

---

## 🗂️ Repository Structure

```text
MatrixMatters/
├── README.md
├── requirements.txt
├── data/
│   └── sample_corpus.txt
└── linear_algebra/
    ├── 01_vectors_and_vector_spaces.ipynb
```

Each notebook follows a **consistent 3-section structure**:

1. **Concepts** — Core mathematical ideas explained visually  
2. **Python Demos** — `numpy`, `matplotlib`, and `scikit-learn` examples  
3. **Real Example (NLP)** — Apply the concept on a tiny corpus of text reviews

---

## 🧠 Topics Covered

| Notebook | Concept Highlights |
|-----------|-------------------|
| **01** | Vectors, vector spaces, linear combinations, span |


---

## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/linear-algebra-for-data-science.git
   cd linear-algebra-for-data-science
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # (Windows: venv\Scripts\activate)
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run notebooks**
   ```bash
   jupyter notebook
   ```
   Then open any file under `linear_algebra/`.

---

## 🧩 Example Corpus

All notebooks use this **shared corpus** stored in `data/sample_corpus.txt`:

```
this movie was amazing and inspiring
the movie was boring and slow
amazing acting but the story was boring
boring movie with terrible acting
```

From this dataset we construct:
- Term-document matrix (Bag-of-Words)
- Word-word co-occurrence matrix
- Derived representations via projections, eigenvectors, and SVD

---

## 🧭 Learning Path

| Level | Focus | Notebooks |
|-------|--------|------------|
| **Foundations** | Vectors, Subspaces | 01–02 |
| **Transformations** | Matrices, Systems, Determinants | 03–05 |
| **Geometry & Projections** | Orthogonality, Special matrices | 06–07 |
| **Advanced** | Eigenvalues, SVD, Decompositions | 08–10 |

---

## 🧑‍💻 Built With

- [Python](https://www.python.org/) 🐍  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [scikit-learn](https://scikit-learn.org/)  
- [Jupyter](https://jupyter.org/)  

---

## 🏁 Goal

> “Turn abstract linear algebra into intuition you can visualize, compute, and use.”

This repository is ideal for:
- Data-science students preparing for interviews or GATE (DA)  
- Professionals revisiting linear algebra for machine learning and NLP  
- Anyone who prefers **code-first** learning over rote theory  

---

## 🤝 Contributing

Pull requests are welcome!  
If you’d like to add new examples, visualizations, or datasets:
1. Fork the repo  
2. Create a new branch  
3. Submit a pull request  

---

## 📄 License

This project is licensed under the **MIT License** — free for educational and commercial use.

---

### ✨ Author
**Anurag Patil**  
_Data Scientist | UC Irvine | NLP & Bayesian Modeling Enthusiast_  
📫 [LinkedIn](https://www.linkedin.com/in/anuragpatil) | [GitHub](https://github.com/<your-username>)
