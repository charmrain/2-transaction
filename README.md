# ❄️ Chiller Energy Consumption Prediction – IKEA An Asian Country 2022

This project uses regression models to **predict the energy consumption of chillers** and **identify key influencing factors**.  
The dataset is based on **IKEA An Asian Country energy usage in 2022**.

---

## 📌 Project Overview

The goal of this project was to:
1. Analyze chiller energy consumption data.
2. Apply **regression models** to predict consumption patterns.
3. Rank the **importance of key factors** affecting performance.
4. Provide insights for potential energy-saving strategies.

---

## 📂 Project Structure

### 1️⃣ Simplified Version – *Chiller 2 & Chiller 3 Models*
- Focused on two specific chillers for quicker analysis.
- Includes basic data cleaning, regression modeling, and feature ranking.
- [View Notebook → **`Chill 2 and 3 models.ipynb`**](https://github.com/charmrain/chiller-energy-prediction/blob/main/Chill%202%20and%203%20models.ipynb)

### 2️⃣ Detailed Version – *Chiller 1 Investigation*
- Includes **in-depth data exploration**.
- Feature engineering for improved model performance.
- Model testing and evaluation metrics comparison.
- [View Notebook → **`investigation and linear model for energy data.ipynb`**](https://github.com/charmrain/chiller-energy-prediction/blob/main/investigation%20and%20linear%20model%20for%20energy%20data.ipynb)

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Jupyter Notebook** for experimentation and documentation
- **Pandas**, **NumPy** – data manipulation
- **Matplotlib**, **Seaborn** – visualization
- **scikit-learn** – regression modeling & feature importance

---

## 📊 Key Steps in Analysis

1. **Data Investigation**
   - Examined chiller operational patterns.
   - Checked data quality and distribution.
   
2. **Feature Engineering**
   - Created derived variables from raw measurements.
   - Encoded categorical data where necessary.

3. **Model Building**
   - Applied linear regression models.
   - Evaluated performance using RMSE and R².

4. **Feature Importance**
   - Ranked contributing factors using model coefficients and statistical significance.

---

## 📈 Results & Insights

- **Chiller-specific analysis** revealed different efficiency patterns.
- Certain operational and environmental variables had a stronger correlation with energy use.
- Feature importance ranking can guide **energy optimization strategies** for similar facilities.

---

## 🚀 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/charmrain/chiller-energy-prediction.git
    ```

2. Open the notebooks in Jupyter:
    ```bash
    jupyter notebook
    ```

3. Navigate to:
    - `Chill 2 and 3 models.ipynb` (simplified analysis)
    - `investigation and linear model for energy data.ipynb` (detailed analysis)

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- IKEA An Asian Country for providing the dataset (2022).
- Open-source Python data science libraries.
