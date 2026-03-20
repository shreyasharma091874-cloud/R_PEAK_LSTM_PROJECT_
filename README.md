# ECG R-Peak Detection using LSTM

This project implements R-peak detection in ECG signals using a Long Short-Term Memory (LSTM) neural network.

## Project Description

Electrocardiogram (ECG) signals are time-series biomedical signals.  
Detecting R-peaks is important for heart rate analysis and medical diagnosis.

In this project, an LSTM-based deep learning model is trained to learn temporal patterns in ECG signals and detect R-peak positions.

## 💻 Softwares Used

- Python 3.10+
- VS Code
- Jupyter Notebook
- Git
- GitHub

## 📦 Libraries Used

- torch (PyTorch)
- numpy
- matplotlib
- wfdb
- sklearn

##  Model Used

- LSTM (Long Short-Term Memory)
- Binary classification for peak detection
- Threshold-based peak extraction

##  Steps Performed

1. Load ECG dataset
2. Preprocess signal
3. Create labels for peaks
4. Train LSTM model
5. Plot training loss
6. Calculate train & test accuracy
7. Predict peaks
8. Plot results
9. Zoomed peak verification
10. Save trained model

##  Results

- Train Accuracy ≈ 0.99
- Test Accuracy ≈ 0.99
- Correct peak detection observed in plots

The model successfully learns temporal patterns in ECG signals.

##  Files in this repo

- `lstm_r_peak.ipynb` → Main notebook
- `lstm_model.pth` → Saved trained model

##  Author

Shreya Sharma  
B.Tech Project – ECG Signal Analysis using LSTM
