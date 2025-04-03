# Music Genre Classification Using XGBoost and Feature Engineering

## Overview
This project explores the task of **classifying music tracks into genres** using various machine learning techniques. Starting with exploratory analysis and traditional deep learning methods like **CNNs and MLPs**, the final and most successful approach uses **XGBoost with engineered features**, achieving a state-of-the-art accuracy of **93%**.

The work is based on the **GTZAN dataset**, and includes experiments, feature analysis, model tuning, and comparisons.

## Key Topics Covered
- Audio signal processing  
- Feature engineering for music data  
- CNN and MLP implementation for classification  
- Hyperparameter tuning with GridSearchCV  
- XGBoost-based classification  
- Evaluation and metrics (Precision, Recall, F1)  
- Embedding techniques using OpenL3  

## Structure
The project includes the following notebooks and components:

1. **Understanding_and_Preprocessing_Audio_Data_GTZAN.ipynb**  
   - Feature extraction (MFCCs, Chroma, Spectral Contrast)  
   - Data visualization and preprocessing  

2. **MLP_VS_RF.ipynb**  
   - Initial experiments using Multi-Layer Perceptron and Random Forest  

3. **CNN.ipynb**  
   - Deep learning model using CNNs trained on spectrograms  

4. **XGBClassifier93.ipynb**  
   - Best performing XGBoost model with 3-second audio clips  
   - Achieves 93% accuracy  

5. **xgb_model1_with_GridSearchCV.ipynb**  
   - Grid search for hyperparameter optimization  

6. **XGBClassifier_openl3.ipynb**  
   - Experiment using OpenL3 embeddings for feature enhancement  

7. **my_xgboost_music_genre_classification.ipynb**  
   - Combined logic and final pipeline  

## Dataset
- **GTZAN**: 1000 audio tracks across 10 genres, each 30 seconds long  
- Sampling rate: 22,050 Hz  
- Genres: Blues, Classical, Country, Disco, Hip-Hop, Jazz, Metal, Pop, Reggae, Rock  

## Performance Summary
| Model            | Accuracy |
|------------------|----------|
| MLP              | 59%      |
| CNN              | 64%      |
| XGBoost (Raw)    | 71%      |
| XGBoost (Segmented + Tuned) | **93%** |

## Future Directions
- Combine XGBoost with deep embeddings (e.g., OpenL3)  
- Explore ensemble learning and transfer learning  
- Extend to real-time inference pipelines  

## Requirements
- Python 3.x  
- XGBoost  
- TensorFlow (for CNN and embeddings)  
- Librosa  
- Scikit-learn  
- Matplotlib, Numpy, Pandas  
