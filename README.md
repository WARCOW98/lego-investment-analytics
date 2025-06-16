# LEGO Investment Strategy: Descriptive & Predictive Analytics

This repository contains a two-phase analytical approach to assess the investment potential of LEGO sets. It combines descriptive statistics and visual insights with machine learning models to identify underpriced sets and optimize LEGO portfolio strategies.

---

## 📁 Case Study Overview

**Author:** Akshay Prabu  
**Focus:** LEGO sets released in 2018–2019  
**Approach:**  
- **Descriptive Analysis** to understand price-per-piece dynamics across themes  
- **Predictive Analysis** using regression models to forecast retail price and value potential

---

## 🧾 Dataset

The dataset includes product attributes like:
- Theme, Subtheme, Piece Count, Minifigures, Box Dimensions
- Retail Price, Weight, Release Year

⚠️ **Note**: *The dataset cannot be shared due to academic copyright restrictions.*

---

## 🧩 Descriptive Analysis Highlights

### Key Insights:
- **Top Themes**: *Star Wars, City, Friends* led in volume; *Creator Expert* and *Technic* had highest average piece counts.
- **Cost Efficiency**: *Architecture* and *Creator* themes offered lowest average price per piece.
- **Franchise Premiums**: *LEGO Movie 2* and *Jurassic World* sets had higher price-per-piece due to licensing.
- **Subtheme Value**:
  - *Brickheadz* had consistent value with lower price-per-piece.
  - *Juniors* sets showed high cost and lower complexity.

### Visualizations:
- 📊 Bar Charts: Price per piece by theme/subtheme
- 🔥 Heatmaps: Price distribution intensity
- 📈 Scatter Plots: Piece count vs price
- 📦 Boxplots: Distribution of value across Brickheadz vs Juniors

---

## 🔮 Predictive Analysis Highlights

### Models:
- **Linear Regression**
  - R² = 0.92; MAE = $8.71 (Full Data)
- **Random Forest** ✅ Best Performer
  - R² = 0.9254; MAE = $5.33

### Value Potential:
- Calculated as **Predicted Price - Actual Price**
- Sets grouped by:
  - Theme + Price Tier
  - Subtheme (Brickheadz, Juniors)
- Identified underpriced sets like:
  - *Garbage Truck (Juniors)*: +$0.55
  - *Downtown Fire Brigade (City - Fire)*: +$3.10
- Flagged overpriced sets like:
  - *Fire Plane*: -$2.10 to -$8.70
  - *Garage Centre*: -$2.50

---

## 📈 Key Takeaways

- Brickheadz consistently deliver lower cost-per-piece and better price predictability.
- Licensed themes (e.g., Star Wars) offer good value when attached to large, detailed sets.
- Predictive models can identify minor price gaps (~$1–$3) with significant investment implications.
- Random Forest models are best suited for capturing non-linear relationships in product attributes.

---

## 🛠️ Tools Used

- Python 3.x
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---



