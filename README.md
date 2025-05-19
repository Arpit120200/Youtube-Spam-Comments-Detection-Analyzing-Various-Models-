# 📌 YouTube Spam Comments Detection – Analyzing Various Machine Learning Models

A Machine Learning-based project aimed at detecting and classifying spam comments on YouTube to help protect users from deceptive links, scams, and fraudulent content. The model evaluates user-generated comments and identifies those that may pose security or privacy threats.

🔍 This project explores multiple ML algorithms to find the most effective classifier for spam detection through cross-validation, performance visualization, and evaluation metrics.

## 🔗 Project Repository Structure  
```

youtube-spam-comments-detection/
├── spam\_comments.csv               # Dataset used for training and testing
├── YouTube\_Spam\_Detection.ipynb   # Jupyter Notebook with preprocessing, modeling, and analysis
├── YouTube\_Spam\_Analysis.pptx     # Presentation summarizing approach, models used, and insights

````

## ⚙️ Key Features

- 💬 **Comment Preprocessing** – Tokenization, lowercasing, stopword removal, and vectorization.
- 🤖 **Multiple ML Models** – Logistic Regression, Decision Tree, Naive Bayes, SVM, Random Forest, and more.
- ✅ **Cross-Validation** – Ensures model robustness and prevents overfitting.
- 📊 **Performance Visualization** – Includes confusion matrices, ROC curves, and model comparison plots.
- 📈 **Evaluation Metrics** – Accuracy, Precision, Recall, F1 Score.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Arpit120200/Youtube-Spam-Comments-Detection-Analyzing-Various-Models-.git
cd Youtube-Spam-Comments-Detection-Analyzing-Various-Models-
````

### 2. Install Dependencies

Ensure you have Python 3.7+ and Jupyter Notebook installed.

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Launch Jupyter and open the notebook to explore preprocessing, model training, and evaluation: jupyter notebook YouTube_Spam_Detection.ipynb


## 📦 Tech Stack

* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
* **Techniques:** NLP Preprocessing, Classification Models, Cross-Validation
* **Tools:** Jupyter Notebook, PowerPoint for result presentation

## 📊 Outcome

* Determined the most accurate and generalizable model for classifying YouTube spam comments.
* Visualized model performance to interpret strengths and weaknesses.
* Created a repeatable framework for spam detection that can be extended to other platforms like Twitter or Reddit.

## 💡 Future Scope
* Integrate model into a live moderation tool or browser extension.
* Extend classification to include **sentiment detection** or **toxicity analysis**.
* Deploy as a **REST API** for real-time spam detection on comment sections.
