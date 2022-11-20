# READEME

## 0. Settings
Please install these libraries, if you don't have them:
- parselmouth
- scikit-learn
- lime
- pandas
- numpy

## 1. Feature Extraction and Analysis
- Feature extraction and analysis is implemented in `feature_extraction_and_analysis.ipynb`
- As a result of this notebook, speech features and text features are extracted, preprocessed, and saved to the files:
    * `train_speech_prepared.csv`
    * `test_speech_prepared.csv`
    * `train_text_prepared.csv`
    * `test_text_prepared.csv` 
- Speech feature extraction process is very time consuming, so please download these prepared files for effiency
    
## 2. Classification
- Classification is implemented in `classification.ipynb`
- Each feature set (speech, text, speech+text) is trained and tested with Random Forest Classifier
- The best model (text) was analysed
- As a result of analysis, `plots/confusion_error_text.png` and `plots/confusion_matrix_text.png` are made.

## 3. Reponse File
- Response to problems are written in `task1_response.pdf`
- The original `task1_response.docx` file is also here, in case `.pdf` doesn't work
