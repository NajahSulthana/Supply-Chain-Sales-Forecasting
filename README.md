This project focuses on predicting sales using a supply chain dataset (DataCo supply chain dataset). 
The main objective is to analyze different factors affecting sales and build a machine learning model to make accurate predictions.

--> Dataset : The dataset includes information such as product price, quantity, discount, and shipping details.(180K+ entries, 53 columns)

--> Data Preprocessing : Handled missing values
                         Removed outliers using IQR method
                         Converted date columns
                         Created new features like: Delivery delay, Shipping duration, Order month and weekday
                          
--> Models Used : Linear Regression, Random Forest, XGBoost  

--> Model overview : Applied K-Fold Cross Validation
                          Used RandomizedSearchCV for hyperparameter tuning
                          Controlled overfitting by limiting model complexity

--> Key Learnings : Importance of feature selection
                    Handling data leakage
                    Model evaluation using cross-validation
                    Balancing accuracy and generalization
