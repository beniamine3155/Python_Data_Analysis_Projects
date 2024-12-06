# Netflix Data Analysis with Python 🎥📊

This project focuses on analyzing Netflix data to uncover insights about Movies, TV Shows, and their various attributes. Through this analysis, you'll explore trends, filter data based on specific criteria, and visualize key findings. The project uses **Python** for data manipulation, exploration, and visualization.

---

## ⚙️ Commands and Techniques Used

Here are the key commands and techniques used in the project:

| **Command**              | **Description**                                                              |
| ------------------------ | ---------------------------------------------------------------------------- |
| `head()`                 | Displays the first N rows of the dataset (default: N=5).                     |
| `tail()`                 | Displays the last N rows of the dataset (default: N=5).                      |
| `shape`                  | Shows the total number of rows and columns.                                  |
| `size`                   | Displays the total number of elements in the dataset.                        |
| `columns`                | Lists all column names.                                                      |
| `dtypes`                 | Shows the data type of each column.                                          |
| `info()`                 | Provides detailed information about the dataset, including memory usage.     |
| `value_counts()`         | Counts unique values in a column.                                            |
| `unique()`               | Lists all unique values in a column.                                         |
| `nunique()`              | Displays the total number of unique values in a column.                      |
| `duplicated()`           | Identifies duplicate rows in the dataset.                                    |
| `isnull()`               | Detects missing (null) values in the dataset.                                |
| `dropna()`               | Removes rows with missing values.                                            |
| `isin()`                 | Filters records that match specific elements.                                |
| `str.contains()`         | Filters records containing a specific substring in a column.                 |
| `str.split()`            | Splits strings in a column into multiple columns.                            |
| `to_datetime()`          | Converts a column to datetime format.                                        |
| `dt.year.value_counts()` | Counts occurrences of each year in a datetime column.                        |
| `groupby()`              | Groups data based on specific criteria for aggregation or transformation.    |
| `sns.countplot()`        | Visualizes counts of unique values in a column as a bar graph using Seaborn. |
| `max()`, `min()`         | Calculates the maximum and minimum values of a column.                       |
| `mean()`                 | Calculates the mean (average) value of a column.                             |

### Additional Topics Covered

- Creating new columns
- Filtering data (single and multiple columns) using `and`/`or`
- Visualizing data with Seaborn library (e.g., bar graphs)

---

## 🔍 Tasks and Questions Addressed

### Data Cleaning Tasks:

1. **Check for duplicate records**: Remove duplicates if any.
2. **Check for null values**: Visualize missing data using a heatmap.

### Analytical Questions:

1. **For "House of Cards", what is the Show ID and who is the Director?**
2. **In which year were the highest number of TV Shows & Movies released?** (Visualize with a bar graph)
3. **How many Movies & TV Shows are in the dataset?** (Visualize with a bar graph)
4. **Show all Movies released in the year 2000.**
5. **List the titles of all TV Shows released in India only.**
6. **Identify the Top 10 Directors who contributed the most TV Shows & Movies to Netflix.**
7. **Find all records where:**
   - Category is "Movie" and Type is "Comedies", OR
   - Country is "United Kingdom".
8. **How many Movies or TV Shows feature Tom Cruise?**
9. **What are the different Ratings defined by Netflix?**
   - **How many Movies have the 'TV-14' rating in Canada?**
   - **How many TV Shows have an 'R' rating released after 2018?**
10. **What is the maximum duration of any Movie/Show on Netflix?**
11. **Which country has the highest number of TV Shows?**
12. **How can we sort the dataset by year?**

---

## 🛠 Tools & Libraries Used

- **Python 3.x**
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Seaborn**: For data visualization.
- **Matplotlib**: For creating plots and graphs.
- **Jupyter Notebook**: For interactive data analysis.

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone <https://github.com/beniamine3155/Python_Data_Analysis_Projects/tree/main/netflix_project>
   ```
