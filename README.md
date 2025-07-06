# 📊 Statistical Implementation Project in Python (Pandas, NumPy, Matplotlib, Scipy)

This project demonstrates 5 essential statistical implementation tasks using Python. It uses **Pandas, NumPy, Seaborn, Matplotlib, and Scipy** to analyze and visualize data, detect outliers, simulate probability distributions, and evaluate statistical fits.

---

## ✅ Project Tasks Covered

### 1. Compute Descriptive Statistics Using Pandas
- Calculates key statistics like:
  - Mean, Median, Mode
  - Variance and Standard Deviation
  - Minimum, Maximum, Quartiles
- Uses `pandas.DataFrame.describe()` for summary view.

📌 **Library Used**: `pandas`

---

### 2. Plot a Histogram and Boxplot of a Numeric Variable
- **Histogram** shows frequency distribution and normality shape.
- **Boxplot** identifies central tendency and outliers using quartiles and whiskers.

📌 **Libraries Used**: `matplotlib`, `seaborn`

---

### 3. Calculate Z-Scores and Filter Outliers
- Calculates z-scores for each data point using:
  \[
  z = \frac{(X - \mu)}{\sigma}
  \]
- Filters out data points where z > 2 or z < -2 (common outlier threshold).

📌 **Library Used**: `scipy.stats.zscore`

---

### 4. Simulate Coin Flips and Compare Empirical Distribution to Theoretical
- Simulates 1000 coin flips (0 = Tails, 1 = Heads).
- Compares:
  - **Empirical probability** from simulation.
  - **Theoretical probability** (should be ~0.5 for a fair coin).

📌 **Libraries Used**: `numpy`

---

### 5. Fit a Poisson Distribution to Count Data and Evaluate Goodness-of-Fit
- Simulates event counts using Poisson distribution (λ = 4).
- Plots histogram of actual data.
- Overlays Poisson Probability Mass Function (PMF) for visual fit check.

📌 **Libraries Used**: `numpy`, `scipy.stats.poisson`, `matplotlib`

---

## 🧰 Requirements

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
