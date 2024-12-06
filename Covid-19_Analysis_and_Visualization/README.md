# COVID-19 Data Analysis with Python 🦠📊

This project analyzes COVID-19 data to uncover insights into the number of confirmed, death, and recovery cases across different regions. By leveraging Python's data analysis libraries, the dataset is explored, cleaned, and visualized to address specific questions related to the pandemic.

---

## ⚙️ Commands and Techniques Used

| **Command**                       | **Description**                                                                               |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| `import pandas as pd`             | Imports the Pandas library for data manipulation and analysis.                                |
| `pd.read_csv()`                   | Reads the CSV file into a Pandas DataFrame.                                                   |
| `df.count()`                      | Counts the number of non-null values in each column.                                          |
| `df.isnull().sum()`               | Detects missing values in the dataset.                                                        |
| `import seaborn as sns`           | Imports the Seaborn library for data visualization.                                           |
| `import matplotlib.pyplot as plt` | Imports the Matplotlib library for creating visualizations.                                   |
| `sns.heatmap(df.isnull())`        | Visualizes missing values in the dataset as a heatmap.                                        |
| `plt.show()`                      | Displays plots created using Matplotlib or Seaborn.                                           |
| `df.groupby('Col_name')`          | Groups data based on unique values in the specified column for aggregation or transformation. |
| `df.sort_values(by=['Col_name'])` | Sorts the entire dataset based on values in the specified column.                             |
| `df[df.Col_1 == 'Element1']`      | Filters rows where `Col_1` has the value 'Element1'.                                          |

---

## 🔍 Analytical Questions Addressed

1. **Show the number of Confirmed, Deaths, and Recovered cases in each Region.**
2. **Remove all the records where the Confirmed Cases are less than 10.**
3. **Identify the Region with the maximum number of Confirmed cases.**
4. **Identify the Region with the minimum number of Death cases.**
5. **Report the number of Confirmed, Deaths, and Recovered cases in India as of 29th April 2020.**
6. **Sort the dataset:**
   - **A:** By the number of Confirmed cases in ascending order.
   - **B:** By the number of Recovered cases in descending order.

---

## 🛠 Tools & Libraries Used

- **Python 3.x**
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For advanced data visualizations.

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone <https://github.com/beniamine3155/Python_Data_Analysis_Projects/tree/main/Covid-19_Analysis_and_Visualization>
   ```
