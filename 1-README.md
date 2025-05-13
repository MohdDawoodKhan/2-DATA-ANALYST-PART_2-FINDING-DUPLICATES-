# 📊 Stack Overflow Developer Survey Dataset Analysis
 
> 🧰 Tools Used: Python, Pandas

---

## ✅ Objectives

This notebook focuses on performing basic data exploration and analysis on the **Stack Overflow Developer Survey dataset**. By the end of this lab, you will be able to:

- Load and preview a real-world dataset.
- Understand the structure and types of data.
- Perform basic statistical operations and extract insights.
- Count unique entries in specific columns.

---

## 🔹 Steps Performed

### 1. Load the Dataset
- The dataset was loaded from a CSV file using **Pandas**.
- The path to the dataset was specified using a remote GitHub link or local path.

### 2. Explore the Dataset
- The first few rows were displayed using `head()`.
- This gave an overview of the columns such as `Employment`, `MainBranch`, `ConvertedCompYearly`, `Country`, etc.

🟢 **Result**: View of tabular data with various attributes related to developers around the world.

### 3. Check the Dataset Dimensions
- Displayed:
  - Number of **rows** (entries/participants).
  - Number of **columns** (features/questions).

🟢 **Result**: Example — 5 rows × 114 columns (actual size may vary).

### 4. Identify Data Types
- Used `.dtypes` and `.info()` to inspect the data type of each column.
- Helped determine which columns are numeric, categorical, or object types.

🟢 **Result**: List of all columns with their respective data types (e.g., `int64`, `float64`, `object`).

### 5. Analyze Compensation Data
- Focused on the `ConvertedCompYearly` column.
- Performed aggregation:
  - **Mean** salary
  - **Median** salary
  - **Maximum** and **Minimum** salary

🟢 **Result**: Statistical summary for annual compensation values.

### 6. Count Unique Countries
- Counted how many unique countries are represented using `Country.nunique()`.

🟢 **Result**: Example — 183 unique countries (value may vary depending on dataset version).

---

## 📚 Dataset Info

- The dataset is collected from a global annual survey conducted by **Stack Overflow**.
- It includes responses from thousands of developers on employment, technology, compensation, and more.

🔗 [Stack Overflow Developer Survey Homepage](https://insights.stackoverflow.com/survey)

---

## 📌 Notes

- Missing values are common in real-world datasets and should be handled appropriately.
- Further analysis (not covered here) may include:
  - Visualizing salary by country
  - Filtering by employment status
  - Grouping responses by tech stack or years of experience

---

## ⚠️ Disclaimer

> This dataset is intended for **educational and research purposes**. Always comply with the original data source's terms of use.
