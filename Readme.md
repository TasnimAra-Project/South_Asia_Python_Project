# 🌏 Exploring Socio-Economic Growth and Environmental Impact in South Asia

This project analyzes the interplay between economic growth, environmental factors, and governance in six South Asian countries over the past two decades. It leverages statistical and visual techniques to understand development patterns and the challenges faced by the region.

---

## ❓ Research Question

**How have economic growth, environmental factors, and governance influenced development trends in South Asia over time?**

---

## 📊 Countries Analyzed

- 🇧🇹 Bhutan  
- 🇧🇩 Bangladesh  
- 🇮🇳 India  
- 🇱🇰 Sri Lanka  
- 🇳🇵 Nepal  
- 🇵🇰 Pakistan  

---

## 📈 Key Components of the Analysis

### 1. **GDP Growth Trends**
- Visualized 20+ years of GDP growth data
- Analyzed impacts of events like COVID-19 on national economies
- Compared steady growth (e.g., Bangladesh) vs. volatility (e.g., Pakistan, Sri Lanka)

### 2. **Correlation Matrix**
- Explored statistical relationships between:
  - GDP per capita
  - Education
  - CO₂ emissions
  - Life expectancy
  - Governance indicators
- Identified which factors most closely align with GDP growth

### 3. **Multivariate Regression**
- Modeled how combinations of variables affect development
- Used `statsmodels` to quantify influence of factors like:
  - Education index
  - Energy use
  - Government effectiveness

---

## 🛠️ Tools & Libraries

The analysis is done in **Python** using:

```python
pandas
numpy
matplotlib
seaborn
statsmodels

##  🛠️ Key Insights
- Bangladesh shows consistent economic growth tied to industrialization and social investment.

- India maintained steady growth but dipped sharply during COVID-19.

- Sri Lanka and Pakistan experienced fluctuating growth due to governance and fiscal crises.

- Education, energy use, and governance emerged as strong predictors of GDP trends.

- Environmental degradation (e.g., CO₂ emissions) has a complex relationship with development, sometimes increasing alongside GDP.

## 📄 Output
You’ll see:

- Line plots of GDP growth

- Correlation heatmaps

- Regression summaries with coefficients and p-values

- Interpretations in markdown cells for clear storytelling

