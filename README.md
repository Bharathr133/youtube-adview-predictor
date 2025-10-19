# 🎬 YouTube Ad View Prediction using PCA & Neural Networks

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-Classification-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-81%25-green)

## 📖 Project Overview
A machine learning system that predicts YouTube video ad view categories using Principal Component Analysis (PCA) for feature reduction and Artificial Neural Networks (ANN) for classification.

## 🎯 Business Problem
Content creators and advertisers need to predict which videos will generate higher ad revenue. This system analyzes video engagement metrics to forecast ad view potential.

## 🏆 Results
| Metric | Score |
|--------|-------|
| Validation Accuracy | 81.00% |
| Best Model Accuracy | 82.58% |
| PCA Components Used | 9 |
| Optimal Components | 7 |

## 🛠️ Technical Implementation
- **Data Preprocessing**: Feature engineering, normalization
- **Dimensionality Reduction**: PCA with optimal component selection
- **Classification**: Neural Network with (100, 50) hidden layers
- **Evaluation**: Cross-validation, confusion matrix, imposter detection

## 📊 Features Used
- Views, Likes, Dislikes, Comments
- Video duration, publish date
- Engagement ratios, category encoding
- 11 original features reduced to optimal PCA components

## 🚀 Quick Start
```bash
# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook youtube_adview_predictor.ipynb

```
📁 Project Structure
```bash
youtube-adview-predictor/
├── youtube_adview_predictor.ipynb  # Main implementation
├── requirements.txt                # Dependencies
├── README.md                       # Project documentation
└── youtube_adview_predictions.csv  # Prediction results
```
## 💼 Real-World Applications
- **Content Creators**: Maximize ad revenue

- **Advertisers**: Optimize ad placement

- **Platforms**: Improve recommendation systems

- **Marketing**: Better campaign planning
## 👨‍💻 Author
Bharath R

**GitHub:** https://github.com/Bharathr133/youtube-adview-predictor.git

📄 License
MIT License
