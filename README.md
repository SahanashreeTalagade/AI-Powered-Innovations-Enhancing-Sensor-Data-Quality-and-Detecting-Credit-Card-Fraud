# Al-Powered-Innovations-Enhancing-Sensor-Data-Quality-and-Detecting-Credit-Card-Fraud

## Overview  
This project leverages *AI techniques* to enhance the quality of sensor data and detect fraudulent credit card transactions. By applying robust data exploration, cleaning, and feature engineering, a *Random Forest model* is trained to accurately classify transactions as fraudulent or legitimate.  

---

## Workflow  

### 1. *Data Exploration*  
- Explored the dataset to understand features, data types, and distributions.  
- Identified missing values and computed descriptive statistics for numerical features.  
- Visualized distributions using histograms and box plots.  
- Analyzed feature correlations using a *correlation matrix* and heatmap.  

### 2. *Data Cleaning*  
- Identified and resolved outliers using *box plots* and the Interquartile Range (IQR).  
- Applied *Winsorizing* to limit the impact of extreme values.  
- Scaled numerical features (Amount and Time) using *StandardScaler* from scikit-learn.  
- Ensured data consistency by addressing unrealistic values and resolving illogical relationships.  

### 3. *Data Splitting*  
- Split the dataset into training, validation, and testing sets using *stratified sampling* to preserve class distribution.  

### 4. *Feature Engineering*  
- Engineered new features to improve model performance, such as:  
  - *Relative transaction amount:* Computed the transaction amount relative to the user’s average amount.  

### 5. *Model Training*  
- Trained a *Random Forest Classifier* using the engineered features.  
- Performed hyperparameter optimization to improve fraud detection accuracy.  

---

## Tools and Libraries  
The following tools and libraries were utilized in the project:  
- *Python 3.x*: Programming language.  
- *Pandas* and *NumPy*: Data manipulation.  
- *Matplotlib* and *Seaborn*: Data visualization.  
- *scikit-learn*: Data preprocessing, feature scaling, and model building.  

---

## Getting Started  

### Prerequisites  
Install the required Python libraries:  
bash
pip install pandas numpy matplotlib seaborn scikit-learn
  
Ensure that the dataset is available in the appropriate directory.  

### Steps  
1. Clone the repository:  
   bash
   git clone https://github.com/SahanashreeTalagade/AI-Powered-Innovations-Enhancing-Sensor-Data-Quality-and-Detecting-Credit-Card-Fraud
     
2. Navigate to the project directory:  
   bash
   cd AI-Powered-Innovations-Enhancing-Sensor-Data-Quality-and-Detecting-Credit-Card-Fraud
     
3. Run the notebook or Python script containing the workflow.  

---

## Results  
The trained *Random Forest model* achieved accurate classification of fraudulent transactions, demonstrating the effectiveness of *feature engineering* and robust preprocessing techniques.  

---

## Contribution  
Contributions are welcome! To contribute:  
- Fork the repository.  
- Create a feature branch.  
- Submit a pull request.  

Feel free to open issues for suggestions or improvements. Collaboration is encouraged!  

--- 

