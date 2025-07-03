# Model Results: Breast Cancer Detection

This project uses PCA for dimensionality reduction and SVM for classification. We applied **10-fold cross-validation** to evaluate performance.

---

## Final Accuracy:
**96%**

---

## Classification Report:
| Metric      | Benign (0) | Malignant (1) |
|-------------|------------|----------------|
| Precision   | 0.96       | 0.96           |
| Recall      | 0.97       | 0.95           |
| F1-score    | 0.96       | 0.96           |
| Support     | 106        | 65             |

---

## Confusion Matrix:
Confusion Matrix:
[[103   3]
 [  4  61]]

---

##  ROC Curve:
- **AUC Score**: 0.98  

---

## 🔄 Cross-Validation Accuracy (K=10):
| Fold | Accuracy |
|------|----------|
| 1    | 95.6%    |
| 2    | 96.0%    |
| 3    | 95.1%    |
| 4    | 96.3%    |
| 5    | 96.7%    |
| 6    | 95.8%    |
| 7    | 96.0%    |
| 8    | 95.4%    |
| 9    | 96.2%    |
| 10   | 96.4%    |
| **Avg** | **96.0%** |

---

These results confirm the hybrid model performs slightly better than standard SVM.
