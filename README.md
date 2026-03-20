# ECG R-Peak Detection using LSTM

This project implements R-peak detection in ECG signals using a Long Short-Term Memory (LSTM) neural network.

## Project Description

Electrocardiogram (ECG) signals are time-series biomedical signals.  
Detecting R-peaks is important for heart rate analysis and medical diagnosis.

In this project, an LSTM-based deep learning model is trained to learn temporal patterns in ECG signals and detect R-peak positions.
##  Project Objective

The objective of this project is to develop a deep learning model for detecting R-peaks in ECG signals using LSTM (Long Short-Term Memory) networks.

ECG signals are time-series biomedical signals, and accurate detection of R-peaks is essential for heart rate calculation and cardiac analysis.

The project aims to train an LSTM model that can learn temporal patterns in ECG signals and correctly identify peak positions.

##  Problem Statement

Manual detection of R-peaks in ECG signals is time-consuming and error-prone.

Traditional signal processing methods may fail in noisy conditions.

Therefore, a deep learning approach using LSTM is implemented to automatically detect peaks with high accuracy.

##  Applications

- Heart rate monitoring
- ECG signal analysis
- Biomedical signal processing
- Arrhythmia detection
- Healthcare AI systems
  

##  Softwares Used

- Python 3.10+
- VS Code
- Jupyter Notebook
- Git
- GitHub

##  Libraries Used

- torch (PyTorch)
- numpy
- matplotlib
- wfdb
- sklearn

 ## Dataset

MIT-BIH ECG dataset was used for training and testing the model.

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
  
##  Future Work

The current model performs well on the available dataset, but further improvements can be made.

Future work may include:

- Using larger ECG datasets
- Trying advanced models such as CNN + LSTM
- Improving noise removal techniques
- Real-time ECG peak detection
- Deploying the model in healthcare applications
  
 ##  Limitations

- Model trained on limited dataset
- Performance may decrease on very noisy signals
- Requires preprocessing before prediction
- Not tested on real-time ECG devices

##  Conclusion

An LSTM-based model was successfully trained to detect R-peaks in ECG signals.

The model achieved high accuracy and correctly identified peak positions in the signal.

This project demonstrates that deep learning methods are effective for time-series biomedical signal analysis.
 
 ##  Author

Shreya Sharma  
B.Tech Project – ECG Signal Analysis using LSTM
