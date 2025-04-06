# NumPy Mini Project: Census Data Analysis

## 📌 Project Overview
This project analyzes census data using NumPy to derive insights about age distribution, race demographics, working hours for senior citizens, and income based on education levels.

## 📂 Files
- **Numpy_MiniProject_Done.ipynb**: Jupyter Notebook containing the complete code and analysis.
- **makeSenseOfCensus.csv**: Dataset used for the analysis (ensure this file is in the same directory or update the path in the notebook).

## 🛠️ Steps Performed

### 1. Data Loading
- Used `np.genfromtxt()` to load the CSV file with `delimiter=','` and `skip_header=1`.
- Verified the data type as a NumPy array.

### 2. Data Appending
- Appended a new record `[[50, 9, 4, 1, 0, 0, 40, 0]]` using `np.concatenate()`.

### 3. Age Analysis
- Extracted the age column and calculated:
  - **Max Age**: 90
  - **Min Age**: 17
  - **Mean Age**: ~38.06
  - **Standard Deviation**: ~13.34

### 4. Race Distribution
- Segregated data by race (column index 2) and identified:
  - **Minority Race**: Race 3 (only 6 citizens).
  - **Majority Race**: Race 4 (848 citizens).

### 5. Senior Citizens' Working Hours
- Filtered citizens aged >60 and calculated:
  - **Total Working Hours**: 2354
  - **Average Working Hours**: ~38.59 (exceeds the government policy of 25 hours/week).

### 6. Income vs. Education
- Compared income for two groups:
  - **High Education** (>10 years): Average income = **0.43**.
  - **Low Education** (≤10 years): Average income = **0.14**.

## 📊 Key Insights
- The country has a wide age range (17–90 years) with an average age of ~38.
- Race 4 is the majority, while Race 3 is the minority.
- **Policy Violation**: Senior citizens work ~38.6 hours/week on average, exceeding the recommended 25 hours.
- **Education Pays Off**: Higher-educated individuals earn ~3x more than those with lower education.

## 🚀 How to Run
1. Clone the repository.
2. Ensure `makeSenseOfCensus.csv` is in the same directory.
3. Open the Jupyter Notebook and run all cells.

## 📝 Dependencies
- Python 3.x
- NumPy
- Jupyter Notebook

---

### Why This README Works:
1. **Clear Structure**: Sections for overview, steps, and insights.
2. **Concise**: Bullet points highlight key actions and results.
3. **Actionable**: Includes setup instructions and dependencies.
