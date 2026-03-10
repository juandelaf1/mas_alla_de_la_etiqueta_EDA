![cabecera-vinedos](https://github.com/user-attachments/assets/78828135-359f-415b-a8e0-894c8142f7ab)


# Exploratory Data Analysis (EDA) of Spanish Wines

## 📌 Objective

Perform an **Exploratory Data Analysis (EDA)** to identify patterns in the Spanish wine market, focusing on:

- The relationship between key attributes such as **price, region and wine type** and their **ratings**.
- The influence of **Denominations of Origin (D.O.) and wine regions** on wine market positioning and perceived quality.

---

## 📋 Hypotheses

### 🔍 Main Hypothesis

**Price–quality relationship:**  
Higher perceived quality is expected to be associated with higher prices and better ratings.

### 🔍 Secondary Hypotheses

- **Well-known regions:** Wines from **La Rioja and Ribera del Duero** tend to receive higher ratings.
- **Less recognized regions:** These regions may stand out due to **strong price–quality value**.
- **Established wineries:** Recognized wineries are expected to achieve **higher ratings regardless of price**.
- **Wine characteristics:** Attributes such as **acidity and body** may be associated with higher ratings and premium prices.

---

## 📂 Data Sources

The analysis uses three datasets:

- **vinos_espana.csv**  
  Dataset containing detailed wine information including **winery, vintage year, rating, price, region and wine type**.

- **totales_vino_y_otros.csv**  
  Dataset describing **wine consumption trends in Spain**.

- **bebidas_c_semanal.csv**  
  Dataset containing **weekly alcoholic beverage consumption statistics**.

---

## 🛠 Data Processing

### 🔧 Data Cleaning

Several preprocessing steps were performed to ensure data quality:

- Standardization of **region names** (lowercase normalization).
- Handling missing values:
  - **type:** inferred using region information.
  - **body and acidity:** imputed using the **regional average values**.
- Removal of rows containing unresolved null values.

### ➗ Dataset Segmentation

To better understand price dynamics, wines were divided into two groups:

- **Wines priced ≤ €100**
- **Wines priced > €100**

This segmentation allows comparison between **mid-range wines and premium wines**.

---

## 📊 Data Analysis

### 📌 Key Statistics

| Variable | Wines ≤ €100 | Wines > €100 |
|--------|--------|--------|
| Average Price | €34.64 | €388.42 |
| Average Rating | 4.23 | 4.53 |

Premium wines show **higher ratings on average**, suggesting a stronger perceived quality.

---

### 🔗 Correlation Analysis

#### Wines ≤ €100
- **Price – Rating:** Moderate correlation (**0.34**)
- **Acidity / Body – Rating:** Weak correlation

#### Wines > €100
- Stronger relationship observed between **price and rating**, indicating that premium wines tend to receive better evaluations.

---

### 📈 Visualizations

Several visualizations were created to support the analysis:

- **Heatmap:** Correlation between key variables.
- **Bar charts:** Variance analysis of price and ratings.
- **Scatter plots:** Visualization of the **price–rating relationship**.

These visualizations help identify patterns in **wine valuation and market positioning**.

---

## 🎯 Key Insights

- **Price–quality relationship:** A moderate correlation exists, particularly stronger in premium wines.
- **Regional influence:** Wines from **La Rioja and Ribera del Duero** tend to achieve higher ratings.
- **Wine characteristics:** Attributes such as acidity and body do not strongly influence ratings for mid-range wines.
- **Winery reputation:** Well-established wineries tend to obtain higher ratings regardless of price.

---

## 💡 Business Implications

Based on the analysis, several strategic insights emerge:

- **Marketing positioning:** Mid-to-high range wines can benefit from emphasizing **price–quality value**.
- **Regional promotion:** Lesser-known regions may gain market attention by highlighting **competitive quality at lower prices**.
- **Brand value:** Winery reputation plays an important role in perceived quality.

---

## 🚀 Future Work

Potential next steps to extend the analysis:

- Analyze **wine consumption trends** using the additional datasets.
- Include additional variables such as:
  - grape variety
  - vintage year
  - aging methods
- Build **predictive models** to estimate wine ratings based on key features.
