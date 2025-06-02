# SleepClass
# 💤 Sleep Stage Classification using EEG, EOG, and EMG Signals

This project uses physiological signals from the PhysioNet Sleep-EDF dataset to classify sleep stages using machine learning and deep learning techniques.

## 📊 Overview

The goal is to develop models capable of classifying sleep stages based on input from:
- **EEG (Electroencephalogram)**
- **EOG (Electrooculogram)**
- **EMG (Electromyogram)**

We explore preprocessing techniques, feature extraction (including power spectral analysis), and model training using classical and deep learning approaches.

## 🧠 Methods

- **Data Source:** [PhysioNet Sleep-EDF Expanded Dataset](https://physionet.org/content/sleep-edfx/1.0.0/)
- **Preprocessing:** Signal filtering, normalization, epoch segmentation
- **Feature Extraction:** Frequency-domain analysis using FFT, power spectral density
- **Models:**
  - Logistic Regression (baseline)
  - Fully Connected Neural Network (MLP)
  - Long Short-Term Memory (LSTM)

## 🛠️ Tools & Libraries

- Python
- NumPy, Pandas
- Scikit-learn
- PyTorch / TensorFlow
- MNE (for EEG signal processing)
- Matplotlib / Seaborn (visualization)

## 📈 Results

Models were evaluated using accuracy, confusion matrices, and F1 scores across 5-class sleep stage classification:
- Wake (W)
- N1 (light sleep)
- N2 (intermediate sleep)
- N3 (deep sleep)
- REM (Rapid Eye Movement)

LSTM models achieved the highest performance, effectively capturing temporal patterns in the signal data.

## 🔍 Future Work

- Expand to multi-night or cross-subject generalization
- Deploy model as an API or web app
- Explore transformer-based architectures for sequence modeling

## 🤝 Acknowledgements

- PhysioNet for providing open access sleep datasets

---

Feel free to fork, cite, or build upon this work!
