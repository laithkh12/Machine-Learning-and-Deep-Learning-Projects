# 🥑 Avocado Price Forecasting using Facebook Prophet

## 📌 Project Overview

This project uses historical retail data to predict avocado prices in the U.S. using **Facebook Prophet**, a time series forecasting tool. The dataset includes weekly sales volume and average price data for both conventional and organic avocados across various U.S. regions in 2018.

---

## 🗂️ Dataset Summary

The dataset includes the following features:

- `Date`: Date of the observation (weekly)
- `AveragePrice`: Average selling price of avocados
- `Type`: Type of avocado (conventional or organic)
- `Year`: Year of sale
- `Region`: U.S. city or region
- `Total Volume`: Total avocados sold
- `4046`, `4225`, `4770`: Volumes by PLU codes for different avocado sizes

📦 **Source:** [Avocado Prices Dataset](https://www.kaggle.com/neuromusic/avocado-prices)

---

## 🔮 Model: Facebook Prophet

Facebook Prophet is a powerful time series forecasting library ideal for datasets with clear seasonal effects and multiple years of historical data.

### Why Prophet?

- Automatically identifies trends and seasonality
- Incorporates holiday effects
- Handles missing data and outliers robustly

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
git clone https://github.com/yourusername/avocado-price-forecast.git
cd avocado-price-forecast
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook AvocadoMarket.ipynb
```

4. Run all cells to generate price forecasts and visualizations.

---

## 📈 Expected Results

- Trend and seasonal decomposition of avocado prices
- Price forecast into future weeks
- Regional and avocado-type-specific predictions

---

## 📚 Further Reading

- [Facebook Prophet Documentation](https://facebook.github.io/prophet/docs/quick_start.html)
- [Prophet Blog by Meta](https://research.fb.com/prophet-forecasting-at-scale)

---

## 📝 License

This project is licensed under the MIT License.
