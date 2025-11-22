# 📊 Python 50K User Data Analysis & Visualization
/
This project is a detailed data science exercise focused on cleaning, classifying, and visualizing a large dataset (50,000 records) of user demographic and contact information. It was completed as a final project for the Data Analysis course at Technical and Vocational Training Organization (Fanni Herfeh-i) in Tehran.

## ✨ Core Features

* **Data Processing:** Efficiently reads and handles a large volume of **50,000 records**.
* **Data Cleaning & Preprocessing:** Handles missing values, duplicates, and standardizes data formats.
* **Classification & Categorization:** Classifies users based on multiple criteria:
    * **Geographical:** Province and City.
    * **Demographic:** Age and Gender.
    * **Contact Info:** Categorization based on phone number characteristics (e.g., "Round" numbers).
* **Data Visualization:** Generates various statistical charts and graphs (e.g., bar charts, histograms, pie charts) to visually represent the distribution of the categorized data. 

[Image of sample data visualization charts]

* **Reporting:** Outputs the final analysis results and generated charts.

## 🛠️ Technologies Used

* **Language:** Python 3
* **Core Libraries:**
    * **`pandas`:** Essential for efficient data loading, cleaning, manipulation, and categorization.
    * **`numpy`:** Used for high-performance numerical operations and array processing.
    * **`matplotlib`:** Employed for generating high-quality static visualizations of the analysis results.

## 🚀 Getting Started

To run the analysis script successfully, you need to install the required libraries and ensure your data file is accessible.

### Prerequisites

* Python 3 installed on your system.
* The required data science libraries:

    ```bash
    pip install pandas numpy matplotlib
    ```

### Data File Requirements

* The project assumes a large dataset (e.g., a **CSV or Excel file**) containing the 50,000 user records. This file should be structured with columns for **phone number, province, city, gender, and age**.
* The data file (e.g., `user_data.csv`) must be placed in the project's root directory.

### Installation and Running

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Python-50K-User-Data-Analysis-Project.git](https://github.com/YOUR_USERNAME/Python-50K-User-Data-Analysis-Project.git)
    cd Python-50K-User-Data-Analysis-Project
    ```
2.  **Ensure Data File is Present** (as noted above).
3.  **Run the Analysis Script:**
    Execute the Python script from your terminal:
    ```bash
    python data_analysis.py
    ```
    (Note: Assuming your main file is named `data_analysis.py`.)

The script will execute the processing steps, print summary statistics to the console, and generate the visualization charts, saving them as image files (e.g., `.png`) in the project directory.

---
