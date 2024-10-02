# NaiveBayes-classifier

Project: Customer Purchase Prediction Using Naive Bayes Classifier

This project aims to predict whether a customer will purchase a product based on their age, salary, and gender, using a Naive Bayes classifier. The model is trained on a dataset containing customer information, which includes these features, and the target variable indicates whether the customer made a purchase after viewing a social media ad.

Key components of the project include:

-Data Processing: Data is cleaned and processed using pandas and numpy. Features such as age, salary, and gender are normalized using StandardScaler to improve model performance.
- Modeling: A Naive Bayes classifier from scikit-learn is used for classification, leveraging its efficiency for small datasets and categorical variables.
- Serialization: The trained model is serialized using pickle to allow for reusability in production.
- Web Deployment: A Flask web application serves the model, allowing users to input customer details (age, salary, gender) through a user-friendly interface. The application returns whether the customer is likely to purchase the product.

This project demonstrates a simple and effective way to deploy a machine learning model for real-time predictions in a web environment.
