# bias-audit-report
# Bias Audit Report — Income Prediction & Gender Bias

This project investigates and mitigates gender bias in a machine learning dataset using the Adult Census Income dataset. It forms part of a group project for the CAPACITI Tech Career Accelerator.

---

## 📊 Project Overview

- 📁 Dataset: [UCI Adult Census Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- 🎯 Goal: Audit the dataset for bias related to gender in predicting income level (>50K)
- ⚠️ Protected Attribute: `sex` (Male vs. Female)
- 🏷️ Target Variable: `income` (<=50K or >50K)

---

## 🧪 Fairness Analysis

### ✅ Metrics Used:
- Statistical Parity Difference
- Disparate Impact
- (Optional: Equal Opportunity Difference)

### ⚖️ Bias Identified:
- Women were less likely to be predicted as earning >50K
- Statistical parity difference and disparate impact revealed unfair outcomes

---

## 🔧 Mitigation Strategy

- 🔄 Reweighing (AIF360): Preprocessing technique to adjust sample weights
- ✅ Improved fairness metrics post-mitigation
- 📈 Results visualized using bar charts for transparency

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `audit.ipynb` | Jupyter notebook with full analysis and mitigation steps |
| `Bias_Audit_Report_Presentation.pptx` | Presentation slide deck |
| `data/adult.csv` | Cleaned version of the dataset |
| `requirements.txt` | Python dependencies |

---

## 🧠 Ethical Considerations

This analysis connects to key AI ethics principles including fairness, accountability, and harm reduction. We reflect on the potential real-world consequences of biased predictions and propose actionable recommendations for dataset improvement and bias-aware model design.

---

## 🔄 How to Reproduce

1. Clone this repo:
   ```bash
   git clone https://github.com/Rosiey-dev/bias-audit-report.git
   cd bias-audit-report
