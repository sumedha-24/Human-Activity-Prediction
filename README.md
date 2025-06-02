# Human Activity Recognition with Wearable Sensors

This project focuses on classifying human activities using data from wearable sensors like accelerometers and gyroscopes.

---

## 📁 Dataset

- **Source:** mHealth & HAR Smartphone datasets
- **Sensors Used:** Accelerometer (alx, aly, alz, etc.), Gyroscope (glx, gly, glz, etc.)
- **Target:** `Activity` label

---

## 🔍 Data Exploration

- Checked data types, missing values, and class balance.
- Visualized activity distribution using bar charts.

---

## 🔧 Preprocessing

- Applied **median filter** to smooth raw sensor signals.
- Segmented continuous activity sequences.
- Downsampled each class to 2000 samples for balance.
- Normalized data using Min-Max scaling.

---

## 🧪 Train/Test Split

- Split the data into 70% training and 30% testing sets.

---

## 🤖 Models Tested

| Model                    | Accuracy  |
|-------------------------|-----------|
| Support Vector Machine  | 93.97%    |
| Gradient Boosting       | 93.40%    |
| K-Nearest Neighbors     | 92.40%    |
| Random Forest           | 80.31%    |
| Logistic Regression     | 56.90%    |

---

## 📊 Visualization

- Plotted raw and filtered signals to observe noise reduction.
- Bar chart comparing model accuracies.

---

## ✅ Conclusion

Support Vector Machine (SVM) achieved the highest accuracy at 93.97%. Wearable sensor data shows strong potential for robust human activity classification.

