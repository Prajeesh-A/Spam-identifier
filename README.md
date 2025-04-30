
# 📧 Spam Identifier - NLP Project

A machine learning project that uses Natural Language Processing (NLP) to classify messages as **spam** or **ham (not spam)**. This project is implemented in a Jupyter Notebook using Python, Scikit-learn, and various NLP techniques.

## 🚀 Features

- Preprocessing of text data (lowercasing, punctuation removal, stopword filtering, stemming)
- Vectorization using CountVectorizer
- Model training using Naive Bayes classifier
- Accuracy and evaluation metrics (confusion matrix, precision, recall, F1-score)
- Interactive prediction of custom input messages

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-learn
- NLTK (Natural Language Toolkit)
- Matplotlib / Seaborn (optional for visualization)

## 📁 Dataset

The dataset used is the **SMS Spam Collection Dataset** which contains 5,572 SMS messages labeled as **ham** or **spam**.

- Format: `label\tmessage`
- Labels: `ham`, `spam`

> *Note:* Ensure the dataset is in the correct format if you plan to retrain the model.

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Prajeesh-A/spam-identifier.git
   cd spam-identifier
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 How to Use

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook NLP_Practice_2.ipynb
   ```

2. Run all cells to train the model and see evaluations.

3. Use the input section at the end of the notebook to test custom messages.

## 📈 Example

```python
Enter message: Congratulations! You've won a free iPhone. Call now!
Prediction: SPAM
```

## ✅ Future Enhancements

- Use of TF-IDF vectorizer
- Comparison with other models (SVM, Logistic Regression)
- Deployment as a web app (Flask or Streamlit)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

Made with ❤️ by [Prajeesh A](https://github.com/Prajeesh-A)
```


