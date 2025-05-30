# Housing Data Analysis

This project performs **Exploratory Data Analysis (EDA)** on the California housing dataset using **Python** libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn`. The aim is to uncover key insights and relationships within the data to better understand housing trends.

## 📁 Dataset

The dataset used is `housing.csv`, which contains information such as:
- Median house value
- Median income
- Number of households
- Total rooms
- Ocean proximity (categorical)
- And more...

---

## 🧰 Tools & Libraries Used

- **Pandas**: Data loading and manipulation  
- **NumPy**: Numerical operations  
- **Matplotlib**: Plotting graphs  
- **Seaborn**: Advanced data visualizations  

---

## 📊 Exploratory Data Analysis Steps

### ✅ Step 1: Load the Dataset
Used `pandas.read_csv()` to load the housing data into a DataFrame.

### ✅ Step 2: Explore the Data
- Used `.info()`, `.describe()`, and `.isnull().sum()` to understand structure and detect missing values.

### ✅ Step 3: Visualizations

1. **Distribution of Median House Value**  
   Shows how house values are distributed across the dataset.

2. **Correlation Heatmap**  
   Highlights relationships between numeric features, especially `median_income` and `median_house_value`.

3. **Scatterplot: Median Income vs Median House Value**  
   Reveals how income affects housing prices.

4. **Distribution of Households**  
   Provides insights into how households are spread across regions.

5. **Countplot: Ocean Proximity**  
   Visualizes the number of houses by distance from the ocean.

---

## 🔍 Key Insights

- **Skewed House Values**: Median house value shows a right-skewed distribution.
- **Income Influence**: Higher median incomes are strongly correlated with higher house values.
- **Household Spread**: Most regions have fewer households, but some outliers exist.
- **Ocean Proximity**: Proximity to the ocean significantly affects housing count and value.

---

## 📌 Conclusion

This EDA provides a foundational understanding of the housing dataset. Future steps could include:
- Building regression models to predict housing prices
- Using feature engineering for better insights
- Identifying regional trends and anomalies

---

## 📎 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/housing-data-eda.git
