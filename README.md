# Weather Data Analysis Using Python and Pandas

This project focuses on analyzing weather data using Python and its data analysis libraries. The goal is to explore the dataset, clean it, and extract meaningful insights from various weather parameters.

* <a href="https://github.com/Dharani1202/Weather-Data-Analysis-using---Pandas/blob/main/weather%20Project_4.ipynb"> View the Project </a>

## About

The project performs exploratory data analysis (EDA) on a weather dataset to identify patterns and relationships among parameters like temperature, wind speed, visibility, humidity, and weather conditions.

All analyses and code are written and executed in a Jupyter Notebook for clear step-by-step understanding.

## Tools & Technologies Used

* **Python (3.x)**
* **Pandas** – for data manipulation and cleaning
* **NumPy** – for numerical operations
* **Matplotlib / Seaborn** – for visualization (if applicable)
* **Jupyter Notebook** – for executing and documenting the analysis
* **CSV Dataset (Weather Data)**

## Data Cleaning & Processing

1. **Handled Missing Values** – Checked for null values in each column using `isnull().sum()` and removed or replaced them as needed.
2. **Data Inspection** – Displayed dataset information, shape, and basic statistics to understand data structure.
3. **Removed Duplicates** – Ensured there were no repeated rows to maintain accuracy.
4. **Data Filtering** – Applied multiple conditions to filter the dataset for specific scenarios.

## Key Analysis & Insights

### 1. Find All Unique “Wind Speed” Values

Used the `unique()` function to list all unique wind speeds recorded in the dataset.

### 2. Find Number of Times When the Weather Is Exactly Clear

Filtered rows where the “Weather” column equals *Clear* to count occurrences.

### 3. Find Number of Times the Wind Speed Is Exactly 4 km/h

Queried the dataset where `Wind Speed_km/h == 4` to find all such records.

### 4. Find and Remove Null Values

Used `isnull().sum()` to check for missing values across all columns and removed them using `dropna()` or `fillna()`.

### 5. Find All Instances When Snow Is Recorded

Filtered rows where the weather condition includes the word *Snow*.

### 6. Find All Instances Where Wind Speed > 24 and Visibility = 25

Applied conditional filtering to display all records meeting both conditions simultaneously.

### 7. Show All Records Where Weather Condition Is Fog

Displayed all entries where the *Weather* column equals *Fog*.

### 8. Find All Instances Where Weather Is Clear and Visibility Is 40

Used multiple condition filters (`Weather == 'Clear'` and `Visibility_km == 40`) to find such cases.

### 9. Find All Instances Where Weather Is Clear and Relative Humidity > 50

Applied condition-based filtering to extract all records satisfying both criteria.

## Insights Summary

* The dataset contains multiple distinct wind speed values.
* Clear weather occurs frequently in the dataset.
* Several records indicate snow or fog conditions, showing seasonal variation.
* Visibility and humidity correlate with specific weather types.
* Null and duplicate data were successfully cleaned for accurate analysis.

---

 * a href="https://github.com/Dharani1202/Weather-Data-Analysis-using---Pandas/blob/main/weather%20Project_4.ipynb"> View the Project </a>

