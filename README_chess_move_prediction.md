# 🧠 Prediction of Chess Moves using Supervised Machine Learning Models

## 📌 Overview
This project explores the use of supervised machine learning models to predict the next move in a chess game based on the current board state and move history. The goal is to assess how accurately various models can anticipate player decisions in structured, strategic gameplay like chess.

> 🧾 **Note:** This project was developed as part of a postgraduate data science programme (MSc exit award: Postgraduate Diploma). The core functionality is complete, with fine-tuning and documentation ongoing.

## 🎯 Objectives
- Preprocess and encode chess game data into a format suitable for ML models  
- Train and evaluate several supervised models on move prediction  
- Compare model performance using appropriate classification metrics  
- Explore feature importance and limitations of algorithmic decision-making in chess

## 🧰 Technologies & Tools
- Python
- scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn
- (Optional: XGBoost / TensorFlow if used)

## 🗂️ Dataset
- Source: [Specify: Lichess / FICS / Kaggle etc.]  
- Contains PGN (Portable Game Notation) data of thousands of real chess games  
- Processed into feature-label pairs where:
  - Features: Board state, player color, move number, etc.
  - Label: Next move (encoded as target class)

## 🧪 Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest  
- K-Nearest Neighbors  
- (Optional: Gradient Boosted Trees, SVM, Neural Networks, etc.)

## 📈 Evaluation
Models were evaluated using:
- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Cross-validation (where applicable)

## 📊 Key Findings
- Simpler models (e.g. logistic regression) struggled with move diversity  
- Ensemble models (e.g. random forest) performed better with contextual patterns  
- Move prediction is highly dependent on game stage and board complexity  
- Feature engineering (e.g., encoding board state) had a major impact on performance

## 📂 Project Structure
```
chess-move-prediction/
├── data/                   # Processed dataset files
├── notebooks/              # Jupyter notebooks for exploration/training
├── models/                 # Trained model files (if saved)
├── report.docx             # Full academic report (if included)
├── requirements.txt        # Dependencies
└── README.md               # This file
```

## 🚀 How to Run
1. Clone this repository  
2. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
3. Run the main notebook or script:  
   ```
   jupyter notebook notebooks/model_training.ipynb
   ```

## 🔍 Future Work
- Test deep learning approaches (e.g., LSTM or transformer-based models)  
- Use reinforcement learning or unsupervised methods for move generation  
- Improve feature encoding with board image representation (e.g. using FEN strings)

## 📜 License
This project is licensed under the MIT License.
