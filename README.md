# News Bias Classification using Machine Learning

Developed a political bias classifier for news articles that identifies whether content leans left, center, or right using a combined Logistic Regression and Support Vector Machine (SVM) model. The model also outputs probability scores for each class, giving users a transparent view of how confidently the model makes its predictions. Completed through the AI4ALL Ignite program while learning Python, natural language processing (NLP), supervised learning, and responsible AI development.

## Problem Statement

Political bias in media plays a powerful role in shaping public opinion. With so much information being published daily, it can be difficult to determine whether an article is presenting a balanced perspective or a biased one. This project seeks to address that by training an AI model that can detect the political leaning of news articles. Our goal is to promote transparency in media consumption and help readers better evaluate the content they consume.

## Key Results 

1. Collected and preprocessed hundreds of labeled news articles with known political leanings
2. Trained a combined Logistic Regression + SVM model for multi-class classification
3. Included probability outputs for each class to promote transparency in predictions
4. Achieved a model accuracy of ~50–60%, showing early promise in bias classification
5. Identified challenges with data imbalance and subjectivity in article tone
6. Evaluated model performance with cross-validation and classification metrics

## Methodologies 

To accomplish this, we used TF-IDF vectorization to convert article text into numerical features, then trained a hybrid model combining Logistic Regression and Support Vector Machine (SVM) for multi-class classification.
To support transparency, we included probability scores to help users understand the confidence of each prediction. We evaluated performance using cross-validation and confusion matrices, while also reflecting on ethical concerns such as fairness and bias in training data.

## Data Sources <!--- do not change this line -->

*Kaggle Datasets: [Link to Kaggle Dataset](https://www.kaggle.com/datasets)*

## Technologies Used <!--- do not change this line -->

- Python
- pandas
- scikit-learn
- NumPy
- Matplotlib / Seaborn (for visualization)

## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Shawn Lin*
- *Godwin Idowu*
- *Yuki Li*
  
- *John Doe ([john.doe@example.com](mailto:john.doe@example.com))*
- *Jane Smith ([jane.smith@example.com](mailto:jane.smith@example.com))*
