# Experiment 3:  Email Spam or Ham Classification using Naïve Bayes, KNN, and SVM

## 🎯 Objective
To classify emails as spam or ham using three classification algorithms: Naïve Bayes, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) and evaluate their performance using accuracy metrics and K-Fold cross-validation

---

## 🧰 Tools & Libraries Used
- **Python 3.10+** – Primary language for implementation
- **NumPy** – Used for efficient numerical operations and array handling
- **Pandas** – Managed datasets, handled missing values, and performed data preprocessing
- **Scikit-learn** – Implemented classifiers (Naïve Bayes, KNN, SVM), performed hyperparameter tuning, and executed 5-fold cross-validation.
- **Matplotlib** – Created performance visualizations such as confusion matrices, ROC curves, and accuracy plots.

---

## 📁 Folder Structure
```bash
ml-expt-2/
├── README.md                        # Overview, tools, file summary, run instructions
├── datasets/
│   └── spambase.csv                 # Dataset for training classification models
├── Experiment-3/
│   ├── expt-3.ipynb                 # Implementation notebook
├── screenshots/
│   ├── balltree.png             
│   ├── kdtree.png
│   ├── kfold.png
│   ├── knn1.png
│   ├── linearsvc.png
│   ├── nbgauss.png
│   ├── polysvc.png
│   └── sigmoidsvc.png
├── Assignment3_ML_Vidarshanaa.pdf  # Lab report
├── Assignment3_ML_Vidarshanaa.tex  # Latex report
└── requirements.txt                # Python packages and versions used
```

## 🚀 Instructions to Execute the Code

1. **Clone the Repository**
```bash
   git clone https://github.com/vidarshanaa15/ml-expt-3.git
   cd ml-expt-3
```

2. **Open the Notebooks**
- **Using Google Colab:**
  - Go to Google Colab
  - Click File > Upload Notebook and upload any .ipynb file from the Experiment-3 folder
  - *Or* paste the GitHub URL directly in Colab to open from repo
    
- **Running Locally with Jupyter Notebook:**
  - Install required packages:
  ```bash
  pip install -r requirements.txt
  ```
  - Then run
  ```bash
  pip install notebook
  jupyter notebook
  ```
  - Navigate to the Experiment-3 folder and open a notebook in your browser

## 📈 Model Performance
Average accuracy from 5-fold cross-validation:

- **Naïve Bayes (Bernoulli)**: `0.8810`
- **K-Nearest Neighbors (k=1)**: `0.7712`
- **Support Vector Machine (Linear Kernel)**: `0.9217`

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
