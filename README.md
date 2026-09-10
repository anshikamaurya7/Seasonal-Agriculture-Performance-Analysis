# 🌾 Seasonal Agriculture Performance Analysis

An exploratory data analysis project that investigates how agricultural performance changes across **Kharif, Rabi, and Zaid seasons**.

The project analyzes agricultural, environmental, resource, production, water-efficiency, and financial variables to identify seasonal patterns and meaningful relationships in the data.

---

## 📌 Project Overview

Agricultural performance can vary considerably between seasons because of differences in environmental conditions, farming practices, resource usage, and economic factors.

This project uses data analysis and visualization techniques to explore these seasonal differences and understand how agricultural outcomes vary across different conditions.

The analysis focuses on:

* Crop yield
* Agricultural production
* Revenue and profit
* Water usage and water efficiency
* Rainfall and temperature
* Soil conditions
* Fertilizer and pesticide usage
* Crop-wise seasonal performance
* Relationships between agricultural variables

---

## 🎯 Objectives

The main objectives of this project are to:

* Explore and understand the agricultural dataset
* Clean and prepare the data for analysis
* Compare agricultural performance across seasons
* Identify important seasonal patterns and trends
* Analyze crop-wise performance
* Investigate relationships between environmental/resource variables and crop yield
* Examine water usage and efficiency
* Analyze economic outcomes such as revenue and profit
* Create meaningful visualizations
* Generate evidence-based insights and recommendations

---

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables**.

### Major categories of variables

| Category         | Examples                                  |
| ---------------- | ----------------------------------------- |
| Location         | State, District                           |
| Crop             | Crop, Season                              |
| Farm             | Farm Area                                 |
| Environment      | Rainfall, Temperature, Humidity, Sunlight |
| Soil             | Soil pH, Soil Moisture                    |
| Nutrients        | Nitrogen, Phosphorus, Potassium           |
| Resources        | Irrigation, Fertilizer, Pesticide         |
| Crop Performance | Yield, Production                         |
| Economics        | Market Price, Cost, Revenue, Profit       |
| Water            | Water Used, Water Efficiency              |
| Risk             | Disease/Pest Risk                         |

The dataset covers three agricultural seasons:

* 🌧️ **Kharif**
* ❄️ **Rabi**
* ☀️ **Zaid**

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization

---

## 🔍 Analysis Performed

### 1. Data Exploration

The dataset was initially explored using:

* Dataset dimensions
* Data types
* First few records
* Missing-value analysis
* Duplicate-value analysis
* Descriptive statistics
* Season distribution

### 2. Seasonal Performance Analysis

Agricultural performance was compared across Kharif, Rabi and Zaid seasons using:

* Average yield
* Average production
* Average revenue
* Average profit
* Water usage
* Water efficiency
* Disease/pest risk

### 3. Crop-wise Analysis

Average yield was calculated for individual crops and compared across seasons.

The analysis includes crops such as:

* Sugarcane
* Maize
* Rice
* Wheat
* Chilli
* Groundnut
* Cotton
* Pulses

### 4. Correlation Analysis

Correlation analysis was used to investigate relationships between numerical agricultural variables and crop yield.

### 5. Environmental Analysis

The project also explores the relationship between **average temperature and crop yield** using a scatter plot.

### 6. Water Efficiency Analysis

Water usage and water efficiency were compared across seasons to understand resource-use differences.

---

## 📈 Key Findings

Based on the analysis:

### Seasonal performance

| Season | Avg. Yield (Tonnes/Ha) | Avg. Production (Tonnes) | Avg. Revenue (INR) | Avg. Profit (INR) |
| ------ | ---------------------: | -----------------------: | -----------------: | ----------------: |
| Kharif |                   5.64 |                    46.31 |            710,719 |           178,915 |
| Rabi   |                   5.08 |                    41.49 |            601,526 |            87,689 |
| Zaid   |                   4.67 |                    38.89 |            519,172 |           -24,805 |

Kharif shows the highest average yield, production, revenue and profit among the three seasons in this dataset.

Zaid records the lowest average values for these performance measures and has a negative average profit.

### Crop performance

Sugarcane has the highest average yield among the analyzed crops, followed by Maize and Rice.

Average Sugarcane yield by season:

* Kharif: **53.46 Tonnes/Ha**
* Rabi: **43.94 Tonnes/Ha**
* Zaid: **38.42 Tonnes/Ha**

### Yield relationships

The correlation analysis shows a strong positive relationship between:

* **Water efficiency and yield**
* **Production and yield**

The correlation between `Water_Efficiency_t_per_1000m3` and `Yield_Tonnes_Ha` is approximately **0.915** in the dataset.

Correlation should be interpreted as an association and does not by itself establish causation.

### Water efficiency

Average water efficiency differs across seasons:

* Kharif: **5.89**
* Rabi: **5.19**
* Zaid: **4.41**

These results indicate that seasonal differences are also visible in resource-use efficiency.

---

## 💡 Insights

The analysis suggests that agricultural performance is not uniform across seasons.

Some important observations include:

1. **Kharif performs strongest overall** across the major performance indicators analyzed.
2. **Zaid shows comparatively weaker economic performance**, including negative average profit.
3. **Sugarcane has substantially higher yield per hectare** than the other crops in the dataset.
4. Water efficiency has a strong association with yield in the available data.
5. Crop performance varies across seasons, showing the importance of considering seasonal conditions during agricultural planning.
6. Environmental, resource and economic variables provide useful dimensions for understanding agricultural outcomes.

---

## 📊 Visualizations

The project includes visualizations for:

* Average Yield by Season
* Average Production by Season
* Average Revenue by Season
* Average Profit by Season
* Average Yield by Crop
* Crop Yield Across Seasons
* Water Efficiency by Season
* Temperature vs Crop Yield
* Correlation Between Agricultural Variables

---

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── README.md
├── seasonal_agriculture_performance_dataset.csv
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── requirements.txt
│
└── images/
    ├── average-yield-by-season.png
    ├── average-production-by-season.png
    ├── revenue-profit-by-season.png
    ├── crop-yield-analysis.png
    ├── seasonal-yield-heatmap.png
    ├── water-efficiency.png
    ├── temperature-vs-yield.png
    └── correlation-heatmap.png
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Seasonal-Agriculture-Performance-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Seasonal-Agriculture-Performance-Analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

### 5. Run the notebook

Run the cells sequentially to reproduce the analysis and visualizations.

---

## 🔮 Future Scope

The project can be extended by:

* Using agricultural data from multiple years
* Adding more detailed weather and market data
* Developing crop-wise seasonal prediction models
* Performing deeper regional analysis
* Developing early-warning insights for crop and pest risks
* Building an interactive dashboard for farmers and agricultural planners

---

## 👩‍💻 Author

**Anshika Maurya**

B.Sc. IT Student
Babasaheb Bhimrao Ambedkar Central University

---

## ⭐ Project Focus

**Data Analytics | Exploratory Data Analysis | Agricultural Analytics | Data Visualization | Python**
