# Self-Guided Machine Learning & Analytics Labs

This directory serves as the repository for self-guided practice labs, featuring custom-coded Python Jupyter Notebooks. These notebooks implement classical machine learning algorithms and exploratory data analysis using **Pandas, NumPy, Scikit-Learn, and Matplotlib**.

---

## 🛠️ Interactive Practice Notebooks Catalog

Below is a detailed map of the practice labs, along with their target algorithms, datasets, and analytics objectives:

| Notebook File | Core Algorithm | Target Dataset | Analysis Focus | Learning Objectives & Techniques |
| :--- | :--- | :--- | :--- | :--- |
| 📓 **[SVR_My_hand_book.ipynb](file:///d:/Edunet%20Foundation%20Internship/Edunet-Foundation-Internship/Practice/SVR_My_hand_book%20(1).ipynb)** | Support Vector Regression (SVR) | `cars_data.csv` | Predicts MSRP (Retail Price) of cars based on specifications. | - Categorical encoding using LabelEncoder.<br>- GridSearchCV hyperparameter tuning (`C`, `epsilon`, `kernel`).<br>- Multi-dimensional feature scaling via StandardScaler. |
| 📓 **[Linear regression.ipynb](file:///d:/Edunet%20Foundation%20Internship/Edunet-Foundation-Internship/Practice/Linear%20regression%20(1)(2).ipynb)** | Simple Linear Regression | `placement.csv` | Models the linear correlation between student CGPA and salary packages. | - Ordinary Least Squares fitting.<br>- Model coefficient and intercept analysis.<br>- Plotting regression fit vs actual parameters. |
| 📓 **[knn_adult_csv.ipynb](file:///d:/Edunet%20Foundation%20Internship/Edunet-Foundation-Internship/Practice/knn_adult_csv%20updated%20(1)%201%20(1).ipynb)** | K-Nearest Neighbors (KNN) | `adult.csv` (Census) | Classifies individuals' income (<=50k or >50k) based on demographics. | - Cleansing anomalous demographic markers.<br>- Distance metric comparison (Euclidean vs Manhattan).<br>- Finding optimal K value through iteration. |
| 📓 **[Iris.ipynb](file:///d:/Edunet%20Foundation%20Internship/Edunet-Foundation-Internship/Practice/Iris.ipynb)** | Multi-Class KNN Classifier | `Iris.csv` | Classifies Iris species (Setosa, Versicolor, Virginica) using flower dimensions. | - Feature visualization using multi-dimensional scatter matrices.<br>- Splitting and cross-validating classification boundaries. |
| 📓 **[Data Analytics.ipynb](file:///d:/Edunet%20Foundation%20Internship/Edunet-Foundation-Internship/Practice/Data%20Analytics.ipynb)** | Exploratory Data Analysis (EDA) | `COVID clinical trials.csv`, `SampleSuperstore.csv` | Identifying data distribution, duplicate profiles, and value summaries. | - Multi-table merges and duplicate cleansing.<br>- Descriptive statistical operations (`describe()`, correlation matrices). |

---

## 📐 Machine Learning Evaluation Metrics Implemented

Each model in this directory was validated using standard industry metrics:

### 1. Regression Metrics
- **Mean Absolute Error (MAE):** Tells us the average magnitude of prediction errors (absolute difference between predicted and actual values).
- **Root Mean Squared Error (RMSE):** Measures the standard deviation of residuals, penalizing larger errors more heavily.
- **R-squared (R² Score):** Indicates the proportion of variance in the target variable that is predictable from the input features (goodness of fit).

### 2. Classification Metrics
- **Accuracy:** The ratio of correctly predicted observations to the total observations.
- **Confusion Matrix:** Evaluates model confusion by mapping True Positives, False Positives, True Negatives, and False Negatives.
