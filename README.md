

---

# DonorsChoose Project Prediction

GitHub Repository: [DonorsChoose Project](https://github.com/venkataseetharam/Donors-choos)

## Introduction
Our project aims to develop a predictive model for the DonorsChoose platform, forecasting the complete funding of projects within a 60-day timeframe. This research encompasses data cleaning, feature engineering, model selection, and hyperparameter optimization. We utilize the extensive DonorsChoose dataset from Kaggle, encompassing over 1.4 million project submissions with detailed information about each project.

## Methodology
### Data Preparation and Exploration
We meticulously prepared the data, which involved removing redundant information, addressing missing values, and converting categorical data into numerical formats. We also employed visualization techniques to gain insights into the dataset's characteristics.

### Feature Engineering
Key to our approach was the creation of sophisticated text features using TF-IDF and TF-IDF weighted Word2Vec methods.

### Model Selection and Evaluation
Our model of choice was a decision tree, fine-tuned using grid search and cross-validation techniques. We used AUC as a key performance metric to refine our model.

### Data Overview
The project leverages over 1.5 million teacher-submitted project proposals from 2000 to 2018. These proposals include detailed information about the teachers, schools, budgets, subject areas, and funding statuses.

## Project Phases
1. **Data Exploration and Visualization:** Initial analysis to understand data distribution and characteristics.
2. **Feature Development:** Enhancing the model's predictive capabilities by creating new features from existing data.
3. **Model Training and Evaluation:** Various models including XGBoost, Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting were assessed using accuracy, precision, recall, and F1-score metrics.
4. **Implementation:** The final models, including XGBoost, Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting, achieved an AUC of 0.88 with the XGboost and TFIDFW2V model.

### Preprocessing Techniques
We incorporated GloVe for word vector generation and undertook rigorous data cleaning and preprocessing. AUC was employed as a critical evaluation metric. The decision tree model was used for making predictions based on attribute optimization.

### LSTM Model
We utilized LSTM (Long Short-Term Memory) networks for handling sequential data like text, with multiple inputs processed through Embedding layers.

### Model Outcomes
- **Model 1:** Achieved an AUC of 0.74.
- **Model 2:** Focused on refining the TF-IDF process, resulting in an AUC of 0.72.
- **Model 3:** Combined text data with other categorical and numerical values, achieving an AUC of 0.74.

## Results and Comparison
Our final model achieved an AUC of 0.73 on the test set, with project cost, title, and description being significant predictors. Our approach differs from previous studies by combining TF-IDF and TF-IDF weighted Word2Vec for text analysis and employing a decision tree for interpretability.

## Conclusion
Through various models, including logistic regression, random forest, XGBoost, and LSTMs, we achieved a top AUC score of 0.88 with XGBoost TFIDF W2V. Our model demonstrates effective prediction capability and highlights the importance of exploring diverse problem-solving approaches.

## Code and Demonstration
The complete code and demonstration are available on our GitHub repository at [DonorsChoose Project](https://github.com/venkataseetharam/Donors-choose). The repository includes all aspects of our project, from data preparation to model evaluation and prediction.

---

Feel free to adjust or add any details as needed for your README file!
