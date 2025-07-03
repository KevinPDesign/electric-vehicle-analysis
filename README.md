# 🚗 Electric Vehicle Specifications Analysis (2025)

This project performs an exploratory data analysis (EDA) on a dataset of electric vehicles (EVs) released in 2025. It explores specifications such as battery capacity, driving range, and energy efficiency to uncover patterns and compare the performance of different manufacturers.

---

## 📌 Objectives

- Explore the distribution of battery capacity and driving range.
- Analyze the relationship between battery size and autonomy.
- Evaluate energy efficiency (km per kWh) of individual models and brands.
- Compare the performance of the top 10 brands by model count.

---

## 🧠 Key Insights

- There is a strong positive correlation between battery capacity and driving range, but efficiency (Wh/km) varies significantly between brands.
- Dacia, Lancia, and Lucid stand out as the most energy-efficient brands, all exceeding 6 km per kWh.
- Among the top 10 brands by number of models, Volkswagen, Audi, and BMW offer the best balance of range and efficiency, while Mercedes-Benz, despite having the most models, ranks lowest in energy efficiency.
- Performance metrics such as top speed, acceleration, fast charging power, and battery size also vary notably across brands.
- Audi and BMW consistently appear among the top 3 performers across multiple performance categories, showcasing well-rounded engineering.
- Mercedes-Benz dominates in model count but lags behind in most performance averages, suggesting a broader but less optimized lineup.


---

## 📊 Tools Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook (via VS Code)

---

## 🗂️ Project Structure

    electric-vehicle-analysis/
├── data/
│ └── electric_vehicles_spec_2025.csv
├── notebooks/
│ └── 01_eda_electric_vehicles.ipynb
├── images/
│ └── visualizations/
│ └── battery_vs_range.png
│ └── efficiency_by_brand.png
├── README.md
└── requirements.txt


---

## 📁 Dataset

- **Source**: [Kaggle – EV Specifications 2025](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025)
- The dataset includes EV specifications such as brand, model, battery capacity (kWh), range (km), torque, and charging speed.

---

## 📌 Next Steps (Optional Enhancements)

- Time-based trend analysis if longitudinal data becomes available.
- Add interactive visualizations using Plotly or Streamlit.
- Build a simple dashboard or report highlighting top models by efficiency and range.

---

## 📬 Contact

Made with ❤️ by **Kevin Plancarte**  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/kpdesign95/).

---


