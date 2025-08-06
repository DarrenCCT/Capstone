# 🧠 Prediction of Chess Moves using Supervised Machine Learning Models (UNFINISHED)

## 📌 Overview
This project explores the use of supervised machine learning models to predict the next move in a chess game based on the current board state and move history. The goal is to assess how accurately various models can anticipate player decisions in structured, strategic gameplay like chess.

> 🧾 **Note:** This project was developed as part of a MSc data science programme (MSc exit award: Postgraduate Diploma). The basic core functionality is complete, with fine-tuning and documentation ongoing. This project was intended to be my capstone project. Should I return to complete my MSc, this project will likely be the basis. This is the work that I had completed towards to before I took the exit award.

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

## 🗂️ Dataset
- Source: Lichess (direct link currently unavailable)
- Contains PGN (Portable Game Notation) data of thousands of real chess games  
- Processed into feature-label pairs where:
  - Features: Board state, player color, move number, etc.
  - Label: Next move (encoded as target class)

## 🧪 Models Used
- SVM 
- Decision Tree Classifier  
- Random Forest
- (More expected to be included later).

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


## 🔍 Future Work
- Test deep learning approaches (e.g., LSTM or transformer-based models)  
- Use reinforcement learning or unsupervised methods for move generation  
- Improve feature encoding with board image representation (e.g. using FEN strings)

## 📜 License
This project is licensed under the MIT License.
