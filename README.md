# NLP Sentiment Classification Project

This project implements an NLP-based sentiment classification model that categorizes social media posts into **Positive**, **Negative**, and **Neutral** sentiments.

## 📌 Project Contents
- **nlp.py** — Complete Python code for preprocessing, TF-IDF vectorization, training Logistic Regression, evaluation, saving the model, and deploying with Gradio.
- **sentimentdataset.csv** — Dataset used for training and testing.
- **README.md** — Project documentation.
- **LICENSE** — MIT license.
- **.gitignore** — Files and folders excluded from the repository.

## 🔧 Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib / Seaborn
- Gradio (for deployment)

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
2. Run the main script:

bash
Copy code
python nlp.py
3. To launch the Gradio app:

bash
Copy code
python nlp.py  # (app launches automatically if included)
📊 Model Summary
-TF-IDF Vectorizer

-Logistic Regression classifier

-Evaluation metrics: Accuracy, Precision, Recall, F1-score
📜 License

This project is licensed under the MIT License.
