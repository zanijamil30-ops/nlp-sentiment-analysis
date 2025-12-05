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

### 1. Install Dependencies
Make sure Python 3.8+ is installed, then run:

pip install -r requirements.txt


### 2. Run the Main Script
This command executes preprocessing, TF-IDF vectorization, model training, evaluation, and model saving:

python nlp.py


### 3. Launch the Gradio App
If the Gradio interface is included in your script, running the same file will start the app:

python nlp.py

A browser window will open where you can enter text and receive sentiment predictions.


## 📊 Model Summary
- TF-IDF Vectorizer  
- Logistic Regression Classifier  
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score  


## 📜 License
This project is licensed under the MIT License.

