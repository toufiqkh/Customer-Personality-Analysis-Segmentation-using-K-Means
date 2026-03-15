Customer Personality Analysis & Segmentation

Unsupervised Machine Learning with K-Means Clustering

Project Overview
This project performs an in-depth analysis of a customer dataset to group individuals into distinct segments based on demographics and purchasing behavior. By identifying these "customer personalities," businesses can optimize marketing strategies and product offerings for specific high-value groups.

Technical Stack
Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Model Deployment: Joblib (for model & scaler persistence)

Environment: Jupyter Notebook

📂 Dataset Description
The dataset contains information on 2,240 customers, including:

Demographics: Age, Education, Marital Status, Income.

Spending Behavior: Amount spent on Wines, Fruits, Meat, Fish, Sweets, and Gold.

Engagement: Recency of purchase, number of web visits, and campaign responses.

⚙️ Workflow
Data Preprocessing: * Handled missing values in the Income feature.

Feature Engineering: Created age-based metrics and simplified categorical labels (e.g., Education & Living Status).

Exploratory Data Analysis (EDA): Identified correlations between income levels and luxury product spending.

Model Building: * Applied StandardScaler to normalize features.

Determined the optimal number of clusters using the Elbow Method.

Implemented the K-Means Algorithm for final segmentation.

Serialization: Exported the trained model (kmeans_model.pkl) and scaler (scaler.pkl) for production readiness.

📊 Key Insights
High-Value Segment: Characterized by high income and high spending on "Wines" and "Meat."

Budget-Conscious Segment: Smaller household sizes with frequent but low-value purchases.

Opportunity Group: Responds well to digital campaigns but has low physical store visits.
