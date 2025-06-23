# Titanic Dataset - Data Cleaning & Preprocessing

This project is part of my **AI & ML Internship**, focusing on cleaning and preprocessing real-world datasets for machine learning models.

## Dataset
- Source: Kaggle Titanic Dataset
- Contains details of passengers on the Titanic, including features like age, sex, ticket class, fare, etc.

## Tasks Completed
1. **Importing the Dataset**
2. **Handling Missing Values**
   - Used median for numerical columns
   - Used mode for categorical columns
3. **Encoding Categorical Variables**
   - Used One-Hot Encoding with `drop_first=True`
4. **Feature Scaling**
   - Applied StandardScaler to numerical columns
5. **Outlier Detection & Removal**
   - Visualized outliers with boxplots
   - Removed them using the IQR method

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Output
Cleaned dataset ready for model building.

