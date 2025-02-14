# Garment_Worker_Productivity_Regression
This project predicts garment worker productivity using machine learning techniques. By analyzing production attributes like overtime, incentives, and worker count, we develop accurate models to assist manufacturers in improving workforce management and operational efficiency. Multiple regression models are evaluated for performance.


## 📌 Project Overview
This project aims to predict the productivity of garment workers based on various production-related attributes. Using machine learning techniques, we analyze key factors such as targeted productivity, overtime, incentives, and worker count to develop an accurate predictive model. The goal is to assist garment manufacturing units in improving workforce management and operational efficiency.

## 📂 Dataset
The dataset consists of multiple features related to garment production. Below are the key attributes:

| Column Name            | Description |
|------------------------|-------------|
| `date`                | Date of record |
| `quarter`             | Quarter of the year (Q1-Q4) |
| `department`          | Department of the worker (sewing/finishing) |
| `day`                 | Day of the week |
| `team`                | Team number |
| `targeted_productivity` | Expected productivity target |
| `smv`                 | Standard Minute Value (SMV) |
| `wip`                 | Work in Progress (WIP) |
| `over_time`           | Overtime hours |
| `incentive`           | Incentives given |
| `idle_time`           | Idle time of workers |
| `idle_men`           | Number of idle workers |
| `no_of_style_change`  | Number of style changes |
| `no_of_workers`       | Number of workers |
| `actual_productivity` | Actual productivity achieved |

## 🔎 Data Processing Workflow
1. **Exploratory Data Analysis (EDA):**
   - Visualize distributions using histograms, box plots, and correlation heatmaps.
   - Identify missing values and anomalies in productivity data.
   
2. **Feature Engineering & Preprocessing:**
   - Encode categorical variables (`department`, `day`, `quarter`).
   - Handle missing values and remove duplicate records.
   - Normalize numerical features for improved model performance.
   - Split the dataset into training and testing sets.

3. **Model Development & Evaluation:**
   - Implement multiple regression models:
     - Linear Regression
     - Polynomial Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - K-Nearest Neighbors (KNN) Regressor
     - Multi-Layer Perceptron (MLP) Regressor
   - Hyperparameter tuning using `RandomizedSearchCV`.
   - Evaluate models using **Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score**.

4. **Feature Importance & Interpretability:**
   - Determine the key drivers of productivity.
   - Assess the impact of temporal and operational factors on model accuracy.
   - Compare model performance and choose the best predictor.

## 🚀 How to Run the Project
### **1️⃣ Clone the Repository**
```sh
$ git clone https://github.com/yourusername/Garment-Worker-Productivity.git
$ cd Garment-Worker-Productivity
```

### **2️⃣ Install Dependencies**
```sh
$ pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
```sh
$ jupyter notebook
```
Open the `Garments_Worker.ipynb` file and execute the cells.

## 📊 Results
- The best-performing model achieves an R² score of **X.XX**, indicating a strong correlation between predicted and actual productivity.
- Features such as **overtime, incentives, and number of workers** have significant impacts on productivity.
- The model can be further optimized with additional real-time features for enhanced prediction accuracy.

## 📌 Future Improvements
- Incorporating **real-time tracking data** for better productivity insights.
- Testing **deep learning architectures** for potential improvements.
- Deploying the model as a **web API** for factory integration.



## 🔚 Conclusion
This project provides valuable insights into garment worker productivity and demonstrates the potential of machine learning in optimizing workforce efficiency. By leveraging various predictive models, we have identified key drivers of productivity, enabling manufacturers to make data-driven decisions. Future enhancements, such as incorporating real-time data and deep learning models, can further improve prediction accuracy and practical applicability. The findings from this study can be instrumental in shaping better workforce management strategies in the garment industry.



