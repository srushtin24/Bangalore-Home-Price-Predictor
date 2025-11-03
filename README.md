# Real Estate Price Prediction: Predicting Home Prices in Bangalore
This project demonstrates the end-to-end Data Science workflow, from data acquisition and preprocessing to model building, evaluation, and web deployment. Using the Bangalore Home Prices dataset from Kaggle, the goal was to predict residential property prices based on multiple features such as location, total square footage, number of bedrooms (BHK), and bathrooms.


🔍 Data Analysis & Preprocessing
- Data Loading & Cleaning: Imported and inspected the raw dataset using Pandas, handled missing values, and standardized feature formats.
- Feature Engineering: Created meaningful attributes to improve model interpretability and predictive power.
- Outlier Detection & Removal:
    - Removed anomalies using business logic and statistical methods (mean, standard deviation).
    - Applied domain-specific filtering, such as eliminating inconsistent bathroom-to-bedroom ratios.
- Dimensionality Reduction: Applied One-Hot Encoding for categorical variables like location, optimizing feature space for linear modeling.


🧠 Model Development & Evaluation
- Built a Linear Regression model using Scikit-learn to estimate housing prices.
- Implemented K-Fold Cross Validation to ensure model robustness and avoid overfitting.
- Tuned hyperparameters using GridSearchCV, selecting the best performing regression model.
- Validated predictions on test samples to confirm practical accuracy and business reliability.


🗂️ Model Export & Integration
- Serialized the trained model using Pickle, ensuring easy reuse for production deployment.
- Created supporting artifact files (columns.json, model pickle) for scalable backend integration.


🌐 Deployment
- Developed a Flask-based REST API that serves real-time predictions.
- Designed an intuitive frontend interface (HTML/CSS/JavaScript) allowing users to input property details and instantly receive predicted prices.
- Integrated the frontend and backend seamlessly, simulating a real-world ML web application.


💡 Core Skills Demonstrated:
Data Cleaning • Exploratory Data Analysis • Feature Engineering • Linear Regression • Outlier Treatment • Dimensionality Reduction • Model Validation (K-Fold CV) • Hyperparameter Tuning • Flask API Development • End-to-End ML Deployment
