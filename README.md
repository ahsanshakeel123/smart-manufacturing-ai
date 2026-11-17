# 🏭 Smart Manufacturing AI System

A production-level AI system for predictive maintenance in manufacturing.

---

## 📊 Dataset
- **Source**: [Kaggle AI4I 2020 Predictive Maintenance Dataset](https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020)
- **Size**: 10,000 rows, 10 features
- **Task**: Predict machine failure before it happens

---

## 🤖 Techniques Used

| Section | Technique | Result |
|---------|-----------|--------|
| 1 | Statistics & Data Analysis | 339 failures detected (3.4%) |
| 2 | Linear Regression | R² = 0.757 (RPM → Torque) |
| 3 | Logistic Regression | 97.2% accuracy |
| 4 | Random Forest | 98.4% accuracy |
| 5 | Neural Network (MLP) | 98.2% accuracy |
| 7 | Numerical Methods | Stress, Temperature, Fluid Flow |
| 8 | LangChain | Manufacturing status classification |
| 9 | Neurosymbolic AI | AI + Rule-based decision making |
| 10 | CLIP | Image + Text matching |

---

## 🔑 Key Results

- **Best Model**: Random Forest (98.4% accuracy)
- **Most Important Feature**: Torque (32%)
- **Machine Stress**: 20,000,000 Pascal → WARNING level
- **Temperature**: Machine reaches 70°C in 12 minutes
- **LangChain**: 5/5 correct classifications
- **CLIP**: 100% correct image-text matching

---

## 🛠️ Technologies

- Python
- Scikit-learn
- PyTorch
- Transformers (HuggingFace)
- LangChain
- CLIP (OpenAI)
- SciPy
- Pandas, NumPy

---

## 🚀 How to Run

1. Open `smart_manufacturing_ai.ipynb` in Google Colab
2. Run Cell 1 first (loads dataset from Kaggle)
3. Run remaining cells in order

---

## 📁 Project Structure

```
smart-manufacturing-ai/
│
├── smart_manufacturing_ai.ipynb  ← Main notebook
└── README.md                     ← This file
```

