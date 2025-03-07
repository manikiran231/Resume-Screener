# Resume Classification Project

This project leverages machine learning to classify resumes into various categories such as Data Science, HR, Web Designing, and more. It includes data preprocessing, feature extraction using `TfidfVectorizer`, and classification using `OneVsRestClassifier` with a `KNeighborsClassifier` estimator.

## Project Overview
The goal of this project is to accurately classify resumes into predefined categories. It involves:
- Cleaning and preprocessing resumes.
- Feature extraction using `TfidfVectorizer`.
- Building and evaluating a classifier using `KNeighborsClassifier` within a `OneVsRestClassifier`.

### Key Features:
- **Training Accuracy:** 0.88
- **Test Accuracy:** 0.79
- **Classification Report:** Detailed precision, recall, and F1-scores for each category.

## Dataset
The dataset contains resumes categorized into 25 unique fields, such as:
- Data Science
- HR
- Web Designing
- Python Developer
- Testing, and more.

### Dataset Insights:
- Total samples: **160**
- Categories distribution visualized using bar plots and pie charts.

## Requirements
Ensure you have the following dependencies installed:
- Python >= 3.7
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk
- wordcloud

Install the requirements via:
```bash
pip install -r requirements.txt
```
git clone https://github.com/your-username/Resume-Screener.git
cd Resume-Screener
## Results
- **Training Accuracy:** 0.88
- **Test Accuracy:** 0.79
- **Key Observations:**
  - Categories like `Java Developer` and `Data Science` show excellent performance with perfect metrics.
  - Certain categories, such as `HR`, face challenges with low recall.
  - Macro and weighted averages for all classification metrics:
    - **Macro Avg Precision:** 0.77
    - **Macro Avg Recall:** 0.71
    - **Macro Avg F1-Score:** 0.72
    - **Weighted Avg Precision:** 0.90
    - **Weighted Avg Recall:** 0.79
    - **Weighted Avg F1-Score:** 0.82

The detailed classification report provides precision, recall, F1-scores, and support for all 25 categories.

## Contributing
Contributions are always welcome! If you have suggestions, improvements, or new features to add, here's how you can contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
