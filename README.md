# Motor Fault Diagnosis Using CNN and Spectrogram

This project presents a simple and effective approach for fault classification in electric motors using synthetic vibration signals. We generate signal data for three conditions: Healthy, Broken Rotor, and Bearing Fault, and convert them into spectrograms.

## 🧠 Technologies Used:
- Python 3.10
- NumPy, SciPy, OpenCV
- TensorFlow / Keras
- Matplotlib, Seaborn

## 📊 Workflow:
1. Generate signal samples (start_fault_project.py)
2. Plot signal examples (plot_signals.py)
3. Convert signals to spectrograms (generate_spectrograms.py)
4. Train a CNN classifier (train_cnn.py)

## 📈 Results:
- Test Accuracy: 100%
- Model: CNN with 2 Conv layers
- Dataset Size: 90 samples (30 per class)

![Confusion Matrix](confusion_matrix.png)

---

## 🧩 Future Work:
- Expand dataset using real-world recordings
- Compare CNN with SVM / Random Forest
- Add Wavelet Transform features

---

Made with ❤️ by [Safa Bazrafshan](mailto:safa.bazrafshan@gmail.com)
