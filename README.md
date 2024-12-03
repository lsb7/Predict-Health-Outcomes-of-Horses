# Predict-Health-Outcomes-of-Horses
Given a Horse Survival dataset containing 29 columns, with a mix of numerical and categorical features, indicating various past medical conditions of horses, evaluate and compare various classification algorithms to predict whether the horse will survive. Examples of some attributes are whether the horse has had surgery in the past, its age and its respiratory rate. The goal of the competition is to build a model with the highest classification accuracy, with ‘outcome’ being the target variable, representing the possible health outcomes for a horse: ‘Lived’, ‘Died’ or ‘Euthanized’.

Machine learning algorithms, including Random Forest and XGBoost, are utilized to train the predictive models. The notebooks begin with importing necessary libraries and dependencies, followed by loading the dataset and preprocessing to prepare the data for modeling. Evaluation metrics such as accuracy, precision, recall, and F1 scores are used to assess the model's performance. Additionally, cross-validation is employed for model optimization.

The model achieved an accuracy of 0.82.
