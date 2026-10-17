# 🔬 Breast Cancer Wisconsin — Diagnostic Classification

> Can 30 measurements of a single cell nucleus predict whether a breast lump is benign or malignant?
![R](https://img.shields.io/badge/R-4.6.1-blue) ![Accuracy](https://img.shields.io/badge/Accuracy-95%25-brightgreen) ![Data](https://img.shields.io/badge/Samples-569-lightgrey)

---
## 🧠 Key Insight
The diagnosis label was assigned by a human pathologist using clinical ground truth — not derived from these features. That makes this a **supervised learning** problem where the model learns the mapping from morphology → malignancy.

## 📊 Data Dictionary (selected columns)
| Column | Meaning | Type | Averaging meaningful? |
|--------|---------|------|-----------------------|
| `id` | Sample identifier | Nominal | ❌ |
| `diagnosis` | B = Benign, M = Malignant | Nominal | ❌ |
| `radius_mean` | Mean nucleus radius (mm) | Continuous | ✅ |
| `texture_mean` | Grey-scale variance of nucleus | Continuous | ✅ |
| `area_mean` | Mean nucleus area (mm²) | Continuous | ✅ |

Full dictionary covers all 32 columns → [see docs/data-dictionary.md]
