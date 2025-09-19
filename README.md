# ⚙️ Predictive Maintenance Model Selection

## 📝 Project Summary
This project is an end-to-end machine learning solution for **predictive maintenance**, focusing on a Time-to-Failure (TTF) dataset for aircraft engines. The goal is to predict when a component is likely to fail, enabling proactive maintenance. The repository provides a comprehensive workflow, including data analysis and a rigorous model selection process for different predictive tasks.

---

## 📂 Repository Contents
The project is organized into the following Jupyter notebooks, each detailing a critical phase of the data science lifecycle:

* **`Exploratory Data Analysis.ipynb`**: A deep dive into the dataset to understand data distributions, feature correlations, and the nature of the TTF variable. This notebook also identifies the need for specialized metrics like **AUC-ROC** due to class imbalance.
* **`Model Selection - Regression.ipynb`**: Compares various regression models to predict the remaining useful life (RUL). It demonstrates that non-linear models like **Random Forest Regressor** significantly outperform linear ones, with an average prediction error of just **±28.63 cycles**.
* **`Model Selection - Binary Classification.ipynb`**: Evaluates models for a binary classification problem (e.g., "Will the engine fail within X cycles?"). It uses an **Expected Value** analysis to link model performance directly to business profit, providing a clear basis for operational decisions.
* **`Model Selection - Multi-Class Classification.ipynb`**: Extends the classification task to a multi-class problem (e.g., "Will the engine fail in 1-5, 6-10, or 11+ cycles?"). It leverages **precision-recall curves** to effectively handle class imbalance and select the best model.

---

## 🛠️ Technologies
* **Python**
* **Pandas**: For data manipulation and analysis.
* **Scikit-learn**: For building and evaluating machine learning models.
* **Matplotlib & Seaborn**: For data visualization and plotting.
* **Numpy**: For numerical operations.

# Predictive-Maintenance
