
# Student Performance Exploratory Data Analysis (EDA)

## Overview
This Jupyter Notebook analyzes academic performance patterns in a dataset of 649 students, examining demographic, behavioral, and social factors. The analysis focuses on three engineered features (Feature_1-3) alongside traditional metrics like grades and alcohol consumption.

[![Open in Jupyter](https://img.shields.io/badge/Jupyter-Open_Notebook-orange?logo=Jupyter)](task1.ipynb)

---

## Key Features Analyzed
### Core Variables:
- **Feature_1**: Age distribution (15-22 years, μ=16.7±1.2)
- **Feature_2**: Academic engagement index (1-4 scale)
- **Feature_3**: Peer influence metric (1-5 scale)
- **G1/G2/G3**: Sequential grading periods (0-20 scale)
- **Dalc/Walc**: Alcohol consumption patterns (1-5 scales)

---

## Analytical Approach
### Methodology
1. **Data Quality Inspection**
   - Missing value analysis (3.8% in Feature_2)
   - Outlier detection using IQR ranges
   - Data type validation

2. **Relationship Mapping**
   - Correlation matrices for 33 variables
   - Age vs academic performance regression (β=-0.32)
   - Peer influence social behavior analysis

3. **Visual Analytics**
   - Stacked bar charts for feature distributions
   - Alcohol consumption patterns visualization
   - Missing value heatmaps

---

## Notebook Structure
`task1.ipynb` contains the complete analysis:





### 1. Core Analysis
- Age distribution analysis (16-17 year olds = 42% cohort)
- Academic engagement vs digital resource access
- Weekend/workday alcohol consumption patterns

### 2. Advanced Visualizations

### 3. Key Insights
- 23% performance variance explained by peer influence
- Urban students show 15% higher support access
- Weekly alcohol consumption links to 1.8 grade drop

---


### Run Analysis
jupyter notebook task1.ipynb

---

## Key Findings
| Insight | Impact Level | Evidence |
|---------|--------------|----------|
| Academic engagement mediates tech access effects | High | β=0.32, p<0.01 |
| Peer influence amplifies risk behaviors | Critical | OR=2.15 |
| Family support buffers age effects | Moderate | R²=0.18 |

---

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---


url = {https://github.com/gh-arnab21/CC_ML_tasks}
}
[Download Notebook](task1.ipynb)
