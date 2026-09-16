# Adult Income Data Analysis – EDA

## 📌 Project Overview

Exploratory Data Analysis (EDA) performed on the **Adult Income Dataset** to understand patterns between demographic and employment-related factors and income.

## 📊 Dataset

* **Rows:** 48,842
* **Columns:** 15
* **Target:** `income` (`<=50K` / `>50K`)

### Key Features

`age`, `workclass`, `education`, `occupation`, `marital-status`, `relationship`, `race`, `gender`, `hours-per-week`, `native-country`, `income`

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 Analysis Performed

* Checked dataset structure and data types
* Identified and handled missing values
* Replaced `?` with `NaN`
* Analyzed age distribution
* Analyzed workclass categories
* Compared gender and income
* Analyzed age vs income
* Created visualizations using Matplotlib and Seaborn
* Performed random sampling of 50% of the dataset

## 📈 Key Findings

* Average age of individuals is approximately **38.64 years**.
* Age ranges from **17 to 90 years**.
* **37,321** individuals are between 17 and 48 years.
* `Private` is the most common workclass.
* Missing values were mainly found in `workclass`, `occupation`, and `native-country`.
* Income was converted into numerical form for analysis:

  * `<=50K → 0`
  * `>50K → 1`

## 📁 Project Structure

```text
Adult-Income-EDA/
│
├── adult.csv
├── Adult_Income_EDA.ipynb
└── README.md
```

## 🚀 Skills Demonstrated

**Python | Data Cleaning | Pandas | Data Visualization | Exploratory Data Analysis | Statistical Analysis**

## 👩‍💻 Author

**Harshitha**
