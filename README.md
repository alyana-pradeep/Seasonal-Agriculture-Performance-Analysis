# Seasonal Agriculture Performance Analysis

A comprehensive data analytics and machine learning project examining how seasonal variations, resource inputs, and environmental factors influence crop productivity and farm profitability across India.

---

## 📌 Project Overview
Agricultural activities are heavily influenced by seasonal variations in environmental conditions, farming practices, and resource availability. This project analyzes a multi-regional agricultural dataset (4,000 farm records across Kharif, Rabi, and Zaid seasons) to uncover operational patterns, evaluate resource efficiencies, and provide evidence-based recommendations for sustainable farm economics.

---

## 🚀 Key Objectives
- **Data Hygiene & Preprocessing:** Address missing values via seasonal median imputation and screen anomalies using IQR outlier detection.
- **Exploratory Data Analysis:** Conduct univariate, bivariate, multivariate, and correlation analyses across agronomic, environmental, and financial parameters.
- **Seasonal Comparisons:** Quantify performance gaps across Kharif, Rabi, and Zaid cropping cycles.
- **Resource Optimization Deep-Dives:**
  1. Evaluate water productivity across irrigation methods (Drip, Flood, Rainfed, Sprinkler).
  2. Measure crop economic viability and profit margins across seasons.
  3. Identify nutrient saturation thresholds and diminishing returns from chemical fertilizers.
- **Predictive Modeling:** Train a Random Forest Regressor to isolate key drivers of harvest yield ($R^2 \approx 0.88$).

---

## 📊 Key Findings & Empirical Insights
1. **Kharif Dominance:** Delivers the highest mean yield (**5.63 t/ha**) and average net profit (**₹1,78,914**), supported by monsoon precipitation averaging 852.1 mm.
2. **Zaid Vulnerability:** Operates at an average net loss (**-₹24,805** per farm) caused by acute thermal stress (31.04°C) and water deficits (299.1 mm rainfall).
3. **Micro-Irrigation Dividend:** Drip irrigation achieves a water productivity of **6.27 t/1,000 m³**, outperforming conventional Flood irrigation (**3.44 t/1,000 m³**) by over 82%.
4. **Irrigation Profit Gap:** Farms utilizing Drip systems average **₹2,19,626** in profit versus **₹73,354** for Flood-irrigated farms, while saving **26.2%** water volume.
5. **Commercial Crop Resilience:** Cash crops (Chilli and Sugarcane) sustain high net profitability across all three cycles (>₹4,40,000 during Zaid).
6. **Grain Seasonality Risks:** Cereal staples (Rice, Wheat, Maize) suffer heavy losses (<-₹1,90,000 per farm) during summer cultivation.
7. **Nutrient Overuse Plateau:** Excessive fertilizer application (>250 kg/ha) delivers <3% incremental yield while inflating operating costs by over ₹1,10,000.
8. **Primary Yield Drivers:** Random Forest feature importance identifies **Soil Moisture**, **Rainfall**, **Irrigation Method**, and **Seed Quality** as the primary determinants of crop yield.

---

## 💡 Policy & Agronomic Recommendations
- **Mandate Micro-Irrigation Transition:** Subsidize Drip/Sprinkler conversions in non-monsoon seasons to curb water consumption by 26% and preserve margins.
- **Crop Diversification & Zoning:** Disincentivize water-intensive grains (Rice/Maize) in summer (Zaid); transition acreage toward drought-tolerant pulses or high-margin horticulture.
- **Precision Fertilizer Management:** Enforce soil-tested fertilizer application caps (<200 kg/ha) to prevent cost overruns.
- **Soil Moisture Conservation:** Subsidize organic and plastic mulching to suppress soil evaporation losses during extreme heat cycles.

---

## 📂 Repository Structure
```text
├── seasonal_agriculture_performance_dataset (2).csv       # Cleaned agricultural dataset (4,000 records)
├── Agriculturalanalysis.ipynb # Google Colab / Jupyter Notebook (34+ modular cells)
├── Major Project_Seasonal Agriculture Performance Analysis. (2).pdf # Project problem statement and rubric guidelines
├── VOIS_Major_Project_PPT_Submission_Template (2).pptx   # Final presentation deck with code & result screenshots
└── README.md                                         # Project summary and documentation
