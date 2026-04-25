#  Iris Data Exploration and Visualization

##  Project Overview
This project is part of a data science assignment focused on exploring the classic **Iris Dataset**. The objective is to perform exploratory data analysis (EDA), summarize statistical properties, and create meaningful visualizations to understand relationships between different flower features.

---

##  Objectives
The main goals of this project are:

- **Data Loading:** Import the Iris dataset using Pandas.
- **Data Inspection:** Understand dataset structure, dimensions, and data types.
- **Statistical Analysis:** Compute key statistics such as mean, median, and standard deviation.
- **Data Visualization:**
  - Scatter Plots → Relationship analysis
  - Histograms (with KDE) → Distribution analysis
  - Box Plots → Outlier detection

---

##  Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

##  Methodology

### 1. Environment Setup
Imported required libraries for data handling and visualization.

### 2. Exploratory Data Analysis (EDA)
- Checked dataset shape and structure
- Viewed initial records using `.head()`
- Verified column types and data integrity

### 3. Statistical Analysis
- Generated summary statistics using `.describe()`
- Grouped dataset by species
- Calculated mean values for each feature per species

### 4. Data Visualization

- **Scatter Plot:**  
  Analyzed relationship between *sepal_length* and *sepal_width* across species.

- **Histogram (KDE):**  
  Examined distribution of *petal_length*.

- **Box Plot:**  
  Compared *petal_width* across species and detected outliers.

### 5. Output Export
- Saved statistical results as CSV files
- Exported visualizations as high-resolution PNG images

---

## 📊 Key Insights

-  **Distinct Clusters:**  
  *Setosa* forms a clearly separable cluster compared to *Versicolor* and *Virginica*.

-  **Bimodal Distribution:**  
  Petal length shows two distinct distribution peaks, indicating strong species variation.

-  **Outliers:**  
  Minor outliers were detected in petal width for certain species.

-  **Species Comparison:**
  - *Setosa* → Smallest petals and overall size
  - *Versicolor* → Medium-sized measurements
  - *Virginica* → Largest overall dimensions

---


