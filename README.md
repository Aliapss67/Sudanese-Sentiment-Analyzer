# Sudanese-Sentiment-Analyzer

---

## Project Description

This is a **Machine Learning project** aimed at performing **Sentiment Analysis** on texts written specifically in the **Sudanese dialect**. The model is trained on a labeled dataset of Sudanese texts to classify the sentiment expressed as either positive or negative.

The Sudanese dialect presents unique linguistic challenges in Natural Language Processing (NLP), and this project seeks to provide an effective solution for addressing these challenges.

## Key Features

* **Sudanese Text Sentiment Analysis:** Classifies texts into "positive" or "negative" sentiment.
* **Custom Data Preprocessing:** Includes text cleaning steps tailored to handle the specific characteristics of the Sudanese dialect.
* **TF-IDF Text Representation:** Utilizes TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical features for machine learning models.
* **Support Vector Machine (SVM) Model:** A robust classifier trained to ensure accurate sentiment predictions.
* **Performance Evaluation:** Includes classification reports and a confusion matrix to assess the model's performance.

## How It Works

The project follows standard sentiment analysis workflow steps:

1.  **Data Loading:** Labeled texts (text with 0 for negative, 1 for positive) are loaded from an Excel file.
2.  **Text Preprocessing:** A simple cleaning process is applied to texts to remove extraneous characters and standardize formatting.
3.  **Text Representation:** Processed texts are transformed into numerical vectors using the TF-IDF technique.
4.  **Model Training:** The data is split into training and testing sets, and a Support Vector Machine (SVM) model is trained on the training data.
5.  **Evaluation:** The model's performance is evaluated using metrics like Accuracy, Precision, Recall, F1-score, and a Confusion Matrix.
6.  **Prediction:** The trained model can then predict the sentiment of new Sudanese texts.

## Requirements

Ensure you have the following Python libraries installed in your environment:

* `pandas`
* `openpyxl`
* `scikit-learn`
* `matplotlib`
* `seaborn`

You can install them using the following command:

```bash
pip install pandas openpyxl scikit-learn matplotlib seaborn
