# Amazon Prime Movies and TV Shows — EDA & Machine Learning

## Project Overview
This project explores the Amazon Prime Movies and TV Shows dataset through Exploratory Data Analysis (EDA) and Machine Learning (ML).

The project analyzes content characteristics, identifies patterns and trends, and builds machine learning models to classify titles as Movies or TV Shows.

## Project Objectives
- Explore and understand the Amazon Prime dataset.
- Perform data cleaning and preprocessing.
- Analyze Movies and TV Shows using visualizations.
- Identify important patterns and trends.
- Build classification models to predict content type.
- Compare model performance and save the best model.

## Dataset
The project uses two datasets:
- `titles.csv` — information about movies and TV shows.
- `credits.csv` — cast and crew information.

## Project Structure
- `Amazon_Prime_EDA.ipynb` — Exploratory Data Analysis.
- `Amazon_Prime_ML.ipynb` — Machine Learning implementation.
- `Amazon_Prime_ML_Submission.zip` — Saved ML models, graphs and results.
- `graphs/` — EDA visualizations.
- `titles.csv.zip` — Titles dataset.
- `credits.csv.zip` — Credits dataset.

## Exploratory Data Analysis (EDA)
EDA includes:
- Data inspection and cleaning.
- Analysis of Movies and TV Shows.
- Content distribution analysis.
- Release year analysis.
- Genre and country analysis.
- Ratings and runtime analysis.
- Data visualization using Matplotlib and Seaborn.

## Machine Learning
The target variable is `type`, which classifies content into:
- MOVIE
- SHOW

### Models Implemented
1. Logistic Regression
2. Random Forest Classifier

### Best Model Results
The Random Forest model achieved the following results in the test evaluation:

- Accuracy: **97.67%**
- Macro F1-score: **0.9527**

The Random Forest model was selected based on its macro F1-score.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Joblib
- GitHub

## How to Run
1. Clone or download this repository.
2. Open the EDA notebook in Google Colab.
3. Upload or connect the required datasets.
4. Run the notebook cells sequentially.
5. Open the ML notebook and connect the datasets.
6. Run the ML workflow to train and evaluate the models.

## Conclusion
This project combines Exploratory Data Analysis and Machine Learning to understand and classify Amazon Prime Movies and TV Shows. The Random Forest model achieved the best performance among the implemented models.

## Author
**Venkata Ganesh Naik**

GitHub: [VenkataGanesh1922](https://github.com/VenkataGanesh1922)
