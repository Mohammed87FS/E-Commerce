*Title:* E-Commerce Text Classification Analysis

*Group Name:* Group 6


### Task Description & Problem Statement 
- *Objective:* To develop a machine learning model that can accurately classify e-commerce text into categories such as Electronics, Clothing & Accessories, Books, and Household.
- *Problem Statement:* With the vast array of products online, manual classification is not feasible. Automating this process increases efficiency and user experience.

*Contribution:* Our group focused on creating an end-to-end machine learning pipeline to address this classification task, from data preprocessing to model evaluation.


### Methodology 

1. *Preprocessing:*
    - Tokenization, lemmatization, and removal of stop words using Spacy.
    - Transformation of text data into a numerical format using TfidfVectorizer.

2. *Modeling:*
    - Selection and training of models: XGBoost and RandomForest classifiers.
    - Hyperparameter tuning with GridSearchCV for optimal model performance.

3. *State of the Art and Literature Analysis:*
    - Reviewed current methodologies and tools in text classification and natural language processing, justifying our choice of TfidfVectorizer for text representation and ensemble methods for classification.


### Experimental results 

- *Model Evaluation Metrics:*
    - Accuracy, F1 score, and confusion matrix for both XGBoost and RandomForest models.
    - The RandomForest model showed a higher F1 score, indicating better performance on our dataset.

- *Model Selection:*
    - Based on the evaluation metrics, we selected RandomForest as our final model.


### Discussion & Conclusion 

- The RandomForest model outperformed the XGBoost model in terms of the F1 score, making it our model of choice.
- The model's high accuracy suggests it can effectively categorize new e-commerce texts, streamlining the product listing process.


