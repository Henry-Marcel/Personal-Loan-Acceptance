# Personal Loan Acceptance Prediction

This project predicts whether a customer will accept a personal loan offer based on demographic, financial, and behavioral data. By analyzing these features and building machine learning models, the project provides actionable insights for targeted marketing and customer segmentation.

## Project Highlights
- Achieved **99% accuracy** and a **0.998 ROC-AUC score** using a Random Forest Classifier.
- Conducted extensive EDA to uncover patterns in customer demographics, financial activity, and loan acceptance trends.
- Provided actionable insights to optimize marketing strategies.

## Dataset
The dataset contains 5,000 customer records, including the following features:
- **Demographic Attributes**: Age, Family size, Education level.
- **Financial Attributes**: Income, Mortgage value, Credit card spending.
- **Behavioral Attributes**: Use of online banking, credit card, and securities accounts.
- **Target Variable**: `Personal Loan` (0 = Not Accepted, 1 = Accepted).

## Workflow
### 1. Data Preprocessing
- Handled missing values and inconsistencies.
- Verified categorical variable ranges and converted string features (e.g., `CCAvg`) to numeric.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions and relationships with histograms, scatter plots, and box plots.
- Key Insights:
  - Higher incomes and credit card spending correlate with loan acceptance.
  - Customers with CD accounts are more likely to accept loans.

### 3. Feature Engineering
- Encoded categorical variables using one-hot encoding and ordinal encoding.
- Scaled numeric features for consistent value ranges.

### 4. Model Building
- **Random Forest Classifier**: Achieved 99% accuracy and a 0.998 ROC-AUC score.
- Compared with Logistic Regression and Decision Tree models.

### 5. Results and Insights
- Income, CCAvg, and Education are the strongest predictors of loan acceptance.
- Customers with higher financial activity are more likely to accept personal loans.

## File Structure
- `data/`: Contains sample dataset (`bank_loan.csv`).
- `notebooks/`: Jupyter notebooks for EDA and model building.
- `visuals/`: Visual outputs like the ROC-AUC curve and feature importance chart.
- `requirements.txt`: Python dependencies for replicating the project.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/personal-loan-acceptance.git
   
2. Navigate to the project directory
   ```bash
   cd personal-loan-acceptance
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Run the notebook:
   ```bash
   jupyter notebook notebooks/Acceptance-Loan-Project.ipynb

Feel free to connect with me on:
LinkedIn 

