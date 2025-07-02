

### ✅ Notebook Summary:

**Project Title**: *Sales Prediction Using Linear Regression*

**Main Components**:

1. **Libraries Used**:

   * `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

2. **Dataset**:

   * A CSV file is loaded (assumed as `advertising.csv` or similar).
   * Contains features like `TV`, `Radio`, `Newspaper` and `Sales`.

3. **Exploratory Data Analysis (EDA)**:

   * Visualizations using `seaborn.pairplot`, `heatmap`.
   * Insights into correlations between ad spends and sales.

4. **Model Building**:

   * Used **Linear Regression** from `sklearn.linear_model`.
   * Splitting dataset into train and test sets.
   * Model trained on features (`TV`, `Radio`, `Newspaper`) to predict `Sales`.

5. **Evaluation**:

   * Metrics used: Mean Absolute Error, Mean Squared Error, R² Score.
   * Visualization of predictions vs actual sales.

---

### 📄 `README.md` for GitHub

````markdown
# 📊 Sales Prediction Using Linear Regression

This project demonstrates how to build a simple linear regression model to predict sales based on advertising budget spent on TV, radio, and newspaper. The project involves data preprocessing, visualization, model training, and performance evaluation.

## 🧠 Project Overview

The objective is to predict the `Sales` of a product based on how much is spent on different advertising channels:

- **TV**
- **Radio**
- **Newspaper**

Using **Linear Regression**, we analyze the impact of each medium and forecast future sales given new ad budgets.

## 📁 Dataset

The dataset used includes the following columns:

- `TV` — Advertising spend on TV
- `Radio` — Advertising spend on Radio
- `Newspaper` — Advertising spend on Newspaper
- `Sales` — Product sales in units

> 📌 *The dataset should be placed in the same directory as the notebook and named accordingly (e.g., `advertising.csv`).*

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📊 Workflow

1. Importing and exploring the data
2. Data visualization using correlation plots and pairplots
3. Splitting the dataset into training and testing sets
4. Training a Linear Regression model
5. Evaluating performance using MAE, MSE, RMSE, R² Score
6. Predicting and visualizing results

## 📈 Model Evaluation

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

These metrics help assess how well the model is performing on unseen data.

## 📷 Visualization

- Pairplots to understand relationships
- Heatmap for correlation matrix
- Scatter plot of actual vs predicted sales

## ✍️ Author

**Trisha Jaiswal**  
📧 Email: [tjaiswal644@gmail.com](mailto:tjaiswal644@gmail.com)  
📍 Location: Rourkela, India  
🔗 [GitHub](https://github.com/trishajais)  
🔗 [LinkedIn](https://linkedin.com/in/trisha-jaiswal)

## 📌 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/sales-prediction.git
cd sales-prediction
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
```

---

Feel free to contribute or raise an issue. Happy Coding! 💻
