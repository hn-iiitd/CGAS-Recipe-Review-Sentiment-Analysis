# Computational Gastronomy: Recipe Review Sentiment Analysis

## Overview
This project focuses on sentiment analysis of recipe reviews using a dataset containing 1.1 million entries. The objective is to classify reviews into sentiment categories while addressing data imbalance challenges. Various machine learning and NLP techniques have been employed to achieve optimal performance.

## Dataset
-  [Kaggle](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions/data) 
- Contains **1.1 million** recipe reviews.
- Addressed class imbalance using **SMOTE, Tomek links, and undersampling**.
- Ratings grouped into three categories:
  - **Poor** (1 & 2)
  - **Neutral** (3)
  - **Positive** (4 & 5)

## Results
- Implemented **Classical ML Models, RNNs, BERT, and RoBERTa**, which significantly improved accuracy compared to previous models.
- Final accuracy results:
  - **SVM Classifier**: 73.20%
  - **RNNs**: 73.19%
  - **BERT**: 84.53%
  - **RoBERTa**: 84.63%

## Future Work
- Implement the best-performing model on the full dataset.
- Optimize hyperparameters for further performance improvements.
- Evaluate additional NLP models for enhanced sentiment classification.
- Consider model interpretability techniques.

## Contributors
- **Harsh Nangia** – [GitHub](https://github.com/hn-iiitd)
- **Ishaan Agrawal** – [GitHub](https://github.com/yourusername)
- **Madhav Kansil** – [GitHub](https://github.com/h13r0ph4nt)

## License
This project is licensed under the MIT License.
