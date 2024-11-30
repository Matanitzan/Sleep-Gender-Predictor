
# Sleep Gender Predictor

## Project Overview
The **Sleep Gender Predictor** is a machine learning project designed to predict the gender of individuals based on sleep efficiency and related data. By leveraging exploratory data analysis (EDA), data preprocessing techniques, and multiple machine learning models, this project demonstrates how data science can uncover meaningful patterns in health-related datasets.

## Key Features
- **Exploratory Data Analysis (EDA):**
  - Investigates trends and correlations in the dataset.
  - Visualizes key metrics for better understanding.
- **Data Preprocessing:**
  - Normalizes features and handles missing values to improve data quality.
- **Machine Learning Models:**
  - Compares models such as Random Forest, K-Nearest Neighbors (KNN), and Naive Bayes.
  - Evaluates model performance using metrics like accuracy, precision, recall, and F1 score.

## Project Structure
- **`EDA_Sleep_Efficiency.ipynb`:** 
  - Notebook performing EDA and exporting cleaned data.
- **`Sleep_Efficiency_after_EDA.ipynb`:** 
  - Notebook for preprocessing and training machine learning models.
- **`data/`:**
  - Contains the dataset files:
    - `Sleep Efficiency after EDA.csv`: Preprocessed dataset used for modeling.
    - `Comparing indices and models.xlsx`: A summary of model performance comparisons.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas`, `numpy`: Data manipulation and analysis.
  - `scikit-learn`: Machine learning model training and evaluation.
  - `matplotlib`, `seaborn`: Data visualization.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Matanitzan/Sleep-Gender-Predictor.git
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the Jupyter Notebooks in order:
   - `EDA_Sleep_Efficiency.ipynb`
   - `Sleep_Efficiency_after_EDA.ipynb`

## Future Directions
- Include additional features such as lifestyle and health metrics to improve model accuracy.
- Explore deep learning techniques for more advanced prediction capabilities.
- Automate the entire pipeline for real-world use cases.

---
This project highlights the intersection of data science and health analytics, emphasizing the importance of EDA and rigorous model evaluation for meaningful insights.
