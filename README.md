# nlp-ml-resume-classifier
 A machine learning and NLP-based project to classify resumes into job categories using text preprocessing, visualization, and predictive modeling.
📁 Dataset
UpdatedResumeDataSet.csv: Contains resumes with a Category column representing the job domain.

📌 Features:
Resume: Text content of the resume.

Category: Target label for classification.

📊 Exploratory Data Analysis
Performed basic EDA on the dataset:

.head(), .tail(), .describe(), .nunique() for data exploration.

Visualized distribution of categories using:

Countplot

Pie chart

🧼 Data Cleaning
Custom function cleanResume() used for:

Removing URLs, mentions, hashtags

Removing punctuation, symbols, and special characters

Also used NLTK for:

Stopword removal

Tokenization

🤖 Model Training
Used machine learning to classify resumes into categories.

Steps:
Data Cleaning

Text Vectorization (likely TfidfVectorizer or similar)

Model training using classifiers like:

K-Nearest Neighbors (KNN)

(Other models if included)

Model Saving:
Used joblib to save the trained model for future inference:

python
Copy
Edit
import joblib
joblib.dump(knn_model, 'knn_model.pkl')
🧠 Libraries Used
pandas

matplotlib, seaborn

nltk

re

sklearn

joblib

🛠 To Run:
Clone the repo or upload the notebook to Google Colab.

Make sure the dataset path is correct:
/content/drive/MyDrive/anushka ml/UpdatedResumeDataSet.csv

Install necessary libraries (Colab-friendly).

Run the cells step-by-step.

📄 License
This project is licensed under the MIT License.
