<p align="center">
  <img src="https://github.com/user-attachments/assets/78828135-359f-415b-a8e0-894c8142f7ab" alt="Spanish Wine EDA Banner" width="800">
</p>

# SPANISH WINE EDA — Beyond the Label: Market Intelligence for Spanish Wines

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-7C8FA6)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **Exploratory analysis of 10,000+ Spanish wines: price, region, variety, and rating relationships.**

---

## Elevator Pitch

**Problem**: The Spanish wine market is fragmented across 60+ regions and 50+ D.O.s (Denominaciones de Origen). Producers, distributors, and retailers lack data-driven insights into how price, region, and wine attributes influence perceived quality and market positioning.

**Hypothesis**: Price and region are the primary drivers of wine ratings, but the relationship differs significantly between mid-range (<=100 EUR) and premium (>100 EUR) segments. Well-known regions like Rioja and Ribera del Duero command premium ratings, while lesser-known regions may offer better value.

**Solution**: A comprehensive EDA of **10,000+ Spanish wines** analyzing **60+ regions** and **50+ D.O.s**, with correlation analysis, price segmentation, and actionable business insights for marketing, regional promotion, and pricing strategy.

---

## Problem

- Wine market is fragmented across 60+ regions
- Producers lack data on price-quality perception
- Distributors can't identify value opportunities
- Consumers lack transparency on wine attributes

## Key Metrics & Findings

| Metric | Value |
|--------|-------|
| Average Price (mid-range) | **€34.64** |
| Average Price (premium) | **€388.42** |
| Average Rating (mid-range) | **4.23 / 5** |
| Average Rating (premium) | **4.53 / 5** |
| Price-Rating Correlation (mid-range) | **0.34** (moderate) |
| Price-Rating Correlation (premium) | **Stronger** |
| Regions Analyzed | **60+** |
| D.O.s Analyzed | **50+** |
| Data Sources | 3 datasets (wines, consumption, weekly beverages) |

## Hypotheses Tested

| Hypothesis | Result | Evidence |
|-----------|--------|----------|
| Higher price = higher rating | ✅ Confirmed | Moderate correlation (0.34 mid-range, stronger premium) |
| Rioja/Ribera del Duero rate higher | ✅ Confirmed | Regional analysis supports premium positioning |
| Lesser-known regions offer value | ✅ Confirmed | Competitive quality at lower price points |
| Acidity/Body predict rating | ❌ Not significant | Weak correlation for mid-range wines |
| Winery reputation drives ratings | ✅ Confirmed | Established wineries score higher regardless of price |

## Business Implications

- **Marketing**: Mid-to-high range wines benefit from price-quality positioning
- **Regional promotion**: Lesser-known regions can compete on value
- **Brand value**: Winery reputation is a key quality signal
- **Pricing strategy**: Premium segment shows stronger price-rating elasticity

## Data Sources

| Dataset | Description |
|---------|-------------|
| vinos_espana.csv | Wine details: winery, vintage, rating, price, region, type |
| totales_vino_y_otros.csv | Wine consumption trends in Spain |
| bebidas_c_semanal.csv | Weekly alcoholic beverage consumption stats |

---

## Author

**Juan de la Fuente** — [@juandelaf1](https://github.com/juandelaf1)

juandelafuentelarrocca@gmail.com
