# Task 1 - Titanic Dataset Analysis

This task involves data preprocessing and exploratory data analysis on the Titanic dataset.

## Steps Performed

1. Loaded the Titanic dataset using Pandas.
2. Cleaned missing values in:
   - `Age`: filled with median by `Pclass` and `Sex`.
   - `Fare`: filled with median by `Pclass`.
   - `Embarked`: filled with the mode.
   - `Cabin`: dropped and replaced with a binary column `Has_Cabin`.
3. Encoded categorical variables using Label Encoding and One-Hot Encoding.
4. Dropped unnecessary columns such as `Name` and `Ticket`.
5. Visualized correlations using heatmaps and bar plots.
6. Scaled the features using StandardScaler for ML model compatibility.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Output

Visualizations show how survival is influenced by gender and class.

## File List

- `Task1_Titanic_Analysis.py` — Main Python script.
- `Titanic-Dataset2.csv` — Dataset file (upload separately).
- `screenshots/` — Any visuals you want to keep as reference.

---

### 📁 How to Run

1. Make sure Python is installed.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Place `Titanic-Dataset2.csv` in the same directory.
4. Run the Python script:
   ```bash
   python Task1_Titanic_Analysis.py
   ```

---

### 🔗 Credits

Dataset Source:https://www.kaggle.com/datasets/yasserh/titanic-dataset
