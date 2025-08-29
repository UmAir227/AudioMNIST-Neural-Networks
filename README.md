# AudioMNIST-Neural-Networks
Implementation of Neural Networks (Scikit-learn, TensorFlow, PyTorch) on AudioMNIST dataset. Extracted MFCC features and compared model performance.
# AudioMNIST Neural Network Classifier 🎙️🤖

This project implements Neural Networks on the **AudioMNIST dataset**, where speakers recorded digits (0–9).  
We extracted **MFCC (Mel-Frequency Cepstral Coefficients)** features from the audio recordings and trained models using **Scikit-learn, TensorFlow, and PyTorch**.

---

## 📌 Features
- Extracted **13 MFCC features** from audio data.
- Implemented Neural Networks using:
  - Scikit-learn MLPClassifier → **94% accuracy**
  - TensorFlow Keras → **87% accuracy**
  - PyTorch (custom NN with DataLoader) → **91% accuracy**
- Evaluated using **Accuracy, Precision, Recall, F1-score, Confusion Matrix**.

---

## 📊 Results
| Framework       | Accuracy |
|-----------------|----------|
| Scikit-learn    | 94%      |
| TensorFlow Keras| 87%      |
| PyTorch         | 91%      |

---

## 🚀 Tech Stack
- Python (Librosa, Numpy, Pandas, Sklearn, TensorFlow, PyTorch)
- AudioMNIST Dataset
- MFCC Feature Extraction

---

## 📂 Files
- `Programming_Assessment_5_Neural_Networks.ipynb` → Main Notebook
- `features.csv` → Extracted features (MFCC + Labels)
- `results_summary.txt` → Model results

---

## 📬 Author
**Muhammad Umair Azeem**  
📌 [LinkedIn](https://linkedin.com/in/m-umair-azeem-458a7723a)  
📌 [GitHub](https://github.com/UmAir227)
