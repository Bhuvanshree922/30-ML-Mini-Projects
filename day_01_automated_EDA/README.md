# Automated EDA Comparison: Sweetviz vs YData Profiling

This project explores and compares two popular Python libraries for **automated exploratory data analysis (EDA)**:

-  [`Sweetviz`](https://github.com/fbdesignpro/sweetviz): Visual, HTML-based EDA reports optimized for comparing datasets
- [`YData Profiling`](https://github.com/ydataai/ydata-profiling): Formerly `pandas-profiling`, provides a deep statistical report for any DataFrame

---


---

##  Features Compared

| Feature                        | Sweetviz                     | YData Profiling              |
|-------------------------------|------------------------------|------------------------------|
|  Summary Stats              | ✅ Yes                       | ✅ Yes                       |
|  Visualizations             | ✅ Rich & Interactive        | ✅ Interactive & Statistical |
|  Train/Test Comparison       | ✅ Native                    | ❌ Manual                    |
|  Data Warnings               | 🚫 Limited                  | ✅ Extensive Alerts          |
|  Correlations                | ❌ Basic                    | ✅ Pearson, Spearman, etc.   |
| Categorical Analysis        | ✅ Value counts, bar charts | ✅ Mode, freq, skewness      |
| Time-Series Support         | ❌ No                        | ✅ Via `tsmode=True`         |
|  Customization               | 🚫 Minimal                  | ✅ Highly Configurable       |
| Report Export               | ✅ HTML                     | ✅ HTML/JSON                 |

---

## Setup

Install all required libraries:

```bash
pip install sweetviz ydata-profiling pandas matplotlib


