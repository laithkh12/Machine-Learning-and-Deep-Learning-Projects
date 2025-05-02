# 📉 Chicago Crime Rate Forecasting using Facebook Prophet

## 📌 Project Overview

This project involves time series forecasting of reported crime incidents in the City of Chicago using the **Facebook Prophet** model. The dataset spans from **2001 to 2017**, and was sourced from the **Chicago Police Department’s CLEAR (Citizen Law Enforcement Analysis and Reporting)** system.

---

## 🗂️ Dataset Summary

Key columns in the dataset include:

- `ID`: Unique identifier for the record
- `Case Number`: Chicago Police RD Number
- `Date`: Date and time of the crime
- `Primary Type`: Major crime category (e.g., THEFT, BATTERY)
- `Description`: Subcategory of the crime
- `Location Description`, `Community Area`, `District`, `Ward`, etc.
- `Latitude` & `Longitude`: Geographic coordinates (redacted for privacy)

📦 **Source:** [Crimes in Chicago Dataset on Kaggle](https://www.kaggle.com/currie32/crimes-in-chicago)

---

## 🔮 Model: Facebook Prophet

**Facebook Prophet** is an open-source time series forecasting tool developed by Meta. It is ideal for datasets with:

- Strong seasonal patterns
- Historical data over multiple years

**Key Features:**

- Automatically detects seasonality (yearly, weekly)
- Supports holiday effects
- Capable of handling missing data and outliers

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- Facebook Prophet (`prophet`)
- Matplotlib / Seaborn

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chicago-crime-prophet.git
cd chicago-crime-prophet
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook ChicagoCrimeRate.ipynb
```

4. Follow the notebook to preprocess data and generate forecasts.

---

## 📈 Expected Results

- Time series plots of historical crime rates
- Forecasts for future crime trends in Chicago
- Visualization of trend and seasonal components

---

## 📚 Further Reading

- [Facebook Prophet Documentation](https://facebook.github.io/prophet/docs/quick_start.html)
- [Prophet Research Blog](https://research.fb.com/prophet-forecasting-at-scale)

---

## 📝 License

This project is licensed under the MIT License.
