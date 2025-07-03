#  Model Explanation: Hybrid PCA + SVM

This breast cancer detection model is built by combining **Principal Component Analysis (PCA)** with **Support Vector Machine (SVM)**.

---

##  Why PCA?

- **Reduces dimensionality** of the original 32 features
- Removes redundant/noisy features
- Helps avoid overfitting
- Speeds up computation

We used PCA to reduce the number of features to the top **5 principal components** based on variance.

---

##  Why SVM?

- SVM is effective for **binary classification**
- Works well with **small-to-medium datasets**
- Can handle both **linear and non-linear** relationships
- Finds the optimal decision boundary (hyperplane)

We used **SVM with a linear kernel** for this dataset.

---

##  Why 10-Fold Cross-Validation?

- Splits data into 10 parts
- Trains on 9 parts and tests on 1, repeated 10 times
- Reduces the chance of overfitting
- Produces a more **reliable performance estimate**

---

##  Flow Summary:

1. **Pre-process** dataset (clean, normalize)
2. **Apply PCA** → retain most significant features
3. **Train SVM** on reduced dataset
4. **Evaluate** using metrics and cross-validation
5. **Compare** with regular SVM to see performance boost

---

This hybrid pipeline ensures a more robust, accurate, and scalable model for early breast cancer detection.
