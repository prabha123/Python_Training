# 🏎️ McLaren Datathon Training Package

Welcome to the **Python Datathon Training**! This repository is designed to train Machine Learning Engineers on Python basics and advanced topics, all wrapped into a fun F1 racing data challenge.

---


## 📦 Repository Structure

```
/Python-training/
├── datasets/
│   ├── F1 data.csv
├── notebooks/
│   ├── ML_Pipeline_scikitlearn.ipynb
│   ├── Text_Analytics.ipynb
|   ├── XGBoost_ml.ipynb
├   ├── python_basic.ipynb
├── requirements.txt
├── .gitignore
├── environment_setup.md
├── README.md
```

---

## 🖥️ Environment Setup (VS Code)

1️⃣ **Install Python 3.9+**
Download from [https://www.python.org/downloads/](https://www.python.org/downloads/) and install.

2️⃣ **Install VS Code**
Download from [https://code.visualstudio.com/](https://code.visualstudio.com/) and install.

3️⃣ **Create Virtual Environment**

```bash
python -m venv venv
```

4️⃣ **Activate Virtual Environment**

* On Windows:

```bash
venv\Scripts\activate
```

* On macOS/Linux:

```bash
source venv/bin/activate
```

5️⃣ **Install Requirements**

```bash
pip install -r requirements.txt
```

6️⃣ **Install Jupyter in VS Code**
Open VS Code, install the "Jupyter" extension, and restart.

7️⃣ **Download NLP Models (if needed)**

```bash
python -m textblob.download_corpora
python -m spacy download en_core_web_sm
```

---

## 📚 Training Sessions

### 🏁 1️⃣ Basic Python + ML (1 hour)

* Python essentials (data types, functions, loops)
* Pandas for data analysis
* Matplotlib and Seaborn for visualization
* Feature engineering
* Simple regression/classification with Scikit-learn

### 🏎️ 2️⃣ Advanced ML + NLP + Statistics (1 hour)

* Scikit-learn pipelines
* XGBoost modeling
* NLP sentiment analysis with NLTK, SpaCy, TextBlob
* Statistical analysis (correlation, regression) with SciPy
* Model evaluation and improvement

---

## 📂 Dataset Details

* **F1 data.csv**: Simulated F1-style data with driver, team, lap times, pit stops etc.
* **press\_articles.csv**: Example text data (press quotes, social media) for sentiment analysis exercises.

---

## 🏗️ How to Use

1️⃣ Clone this repository:

```bash
git clone https://github.com/prabha123/Python_Training.git
```

2️⃣ Follow the `environment_setup.md` guide.

3️⃣ Open VS Code, launch the notebooks, and follow along with the exercises.

4️⃣ Run `.py` scripts if you prefer working outside Jupyter.

---

## 🧾 requirements.txt

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
nltk
spacy
textblob
scipy
jupyter
```

---

## 📄 .gitignore

```txt
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# Virtual environment
venv/

# VS Code settings
.vscode/

# Jupyter Notebook checkpoints
.ipynb_checkpoints/

# Mac & Linux files
.DS_Store
*.swp
```

---

If you want me to **generate the datasets, notebooks, and scripts** next — let’s get rolling! 🏁
