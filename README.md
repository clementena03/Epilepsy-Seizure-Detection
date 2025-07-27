# Epilepsy-Seizure-Detection

Developed an automated EEG signal classification system to detect epilepsy with and without seizures. Implemented and evaluated ML and DL models like Random Forest (97%), 2D CNN(99%) and ResNet18 (98%) for accurate and real-time seizure detection.

# Objective

To design a robust seizure detection system that accurately classifies EEG signals using machine learning and deep learning models, enabling future real-time implementation in embedded systems.

# Dataset

EEG data collected from three categories:
- Normal individuals
- Individuals with epilepsy (no seizure)
- Individuals with epilepsy (with seizure)

Files:   
`normal_data.xlsx`, `epilepsy_without_seizure_data.xlsx`, `epilepsy_with_seizure_data.xlsx`  
`eeg_features.xlsx`: Pre-extracted statistical features for ML models


# Models Used

Machine Learning: 
   - Random Forest
   - SVM
   - Logistic Regression
   - KNN
   - Gradient Boosting
Deep Learning:
  - 1D CNN
  - GRU
  - LSTM
  - 1D CNN + GRU
  - 1D CNN + LSTM
  - 2D CNN (on spectrograms)  
  - ResNet18 Transfer Learning

# Accuracy Highlights

| Model                          | Accuracy |
|-------------------------------|----------|
| Random Forest                 | 97%      |
| SVM                           | 93%      |
| Logistic Regression           | 92%      |
| KNN                           | 93%      |
| Gradient Boosting             | 96%      |
| 2D CNN (on spectrograms)      | 99%      |
| ResNet18 Transfer Learning    | 98%      |
| 1D CNN                        | 99%      |
| GRU                           | 72%      |
| LSTM                          | 73%      |
| 1D CNN + GRU                  | 93%      |
| 1D CNN + LSTM                 | 95%      |

# Folder Structure
Epilepsy-Seizure-Detection/
│
├── data/ # EEG datasets and extracted features
│ ├── normal_data.xlsx
│ ├── epilepsy_without_seizure_data.xlsx
│ ├── epilepsy_with_seizure_data.xlsx
│ └── eeg_features.xlsx
│
├── notebooks/ # Model training notebooks
│ ├── EEG_ML.ipynb
│ ├── 1D CNN.ipynb
│ ├── GRU.ipynb
│ ├── LSTM.ipynb
│ ├── 1D CNN + GRU.ipynb
│ ├── 1D CNN + LSTM.ipynb
│ ├── 2D CNN.ipynb
│ └── Transfer learning (ResNet18).ipynb
│
├── documents/ # Reports and presentations
│ ├── mini_project.pptx
│ ├── report.pdf
│ └── Algorithm.docx
│
├── requirements.txt # Python libraries used
├── LICENSE # MIT License
└── README.md # This file

# How to Run

1. Clone the repo  
```bash
git clone https://github.com/clementena03/Epilepsy-Seizure-Detection.git
cd Epilepsy-Seizure-Detection

2.Install dependencies
pip install -r requirements.txt

3.Run Notebooks
- Open any .ipynb file in Google Colab or Jupyter Notebook
- Run cells to train/evaluate the models

# **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# **👤 Author**

**Clementena J**  
B.Tech - Electronics and Communication Engineering  
GitHub: [@clementena03](https://github.com/clementena03)





                                                  T     his project was developed as part of my undergraduate mini-project 
