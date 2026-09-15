# Insurance Dataset — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an insurance dataset stored in CSV format.

The main objective is to understand the structure of the dataset, identify patterns and relationships between variables, detect missing values and outliers, and generate useful insights through statistical analysis and data visualization.

##  Dataset

The dataset contains information about insurance customers and their insurance charges.

Typical features include:

* **age** — Age of the customer
* **sex** — Gender of the customer
* **bmi** — Body Mass Index
* **children** — Number of children/dependents
* **smoker** — Whether the customer is a smoker
* **region** — Residential region of the customer
* **charges** — Medical insurance charges

> Note: The exact columns depend on the CSV dataset being used.

##  EDA Performed

The analysis includes:

1. **Data Loading**

   * Read the CSV dataset using Pandas.
   * Inspect the shape and structure of the data.

2. **Data Understanding**

   * Examine column names and data types.
   * Generate descriptive statistics.
   * Identify categorical and numerical variables.

3. **Data Cleaning**

   * Check for missing values.
   * Check for duplicate records.
   * Handle inconsistent or invalid values where necessary.

4. **Univariate Analysis**

   * Analyze individual numerical and categorical variables.
   * Use histograms, count plots, and box plots.

5. **Bivariate Analysis**

   * Study relationships between variables.
   * Analyze factors affecting insurance charges.

6. **Correlation Analysis**

   * Calculate correlations between numerical variables.
   * Visualize relationships using a correlation heatmap.

7. **Outlier Detection**

   * Identify potential outliers using box plots and statistical methods.

## 📊 Key Questions

Some of the questions explored in this project are:

* Does age affect insurance charges?
* How does BMI relate to insurance charges?
* Do smokers have higher insurance charges?
* Does the number of children affect insurance charges?
* Are insurance charges different across regions?
* What factors appear to have the strongest relationship with insurance charges?

## 🛠️ Technologies Used

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Interactive analysis

##  Project Structure

```text
insurance-eda/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── insurance_eda.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```



### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the notebook

```bash
jupyter notebook
```

Open the EDA notebook and run the cells to reproduce the analysis.

##  Results

The analysis provides insights into the factors associated with medical insurance charges and uses visualizations to make patterns and relationships easier to understand.

The complete findings and visualizations are available in the Jupyter Notebook.

## 👤 Author

**Your Name**

---

⭐ If you found this project useful, consider giving the repository a star!
