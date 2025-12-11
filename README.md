# Bank Housing Loan Prediction with Vertex AI AutoML 🚀

**90-minute no-code ML portfolio project: Predicts active housing loans using Google Vertex AI AutoML**

## 📊 Business Problem
Predict whether bank customers have active housing loans (`loan: yes/no`) to enable targeted marketing and risk segmentation.

## 🔧 Tech Stack

Platform: Google Cloud Vertex AI AutoML Tabular
Dataset: UCI Bank Marketing (45,211 rows × 17 columns)​
Target: loan (binary classification)
Training: 1 node-hour budget
Deployment: Live prediction endpoint

## 📈 Dataset Overview
| Feature | Type | Description |
|---------|------|-------------|
| age | Numeric | Customer age |
| job | Categorical | Customer occupation |
| marital | Categorical | Marital status |
| balance | Numeric | Account balance |
| housing | Categorical | Has housing loan? |
| **loan** | **Target** | **Has personal loan?** |
| duration | Numeric | Call duration |
| ... + 10 more | Mixed | Campaign details |

## 🤖 No-Code Workflow

Uploaded bank.csv → Vertex AI Datasets
Set loan as binary classification target
Trained AutoML (1 node-hour)
Evaluated metrics + feature importance
Deployed to online prediction endpoint

## 📊 Results

| Metric               | Value  | Benchmark |
| -------------------- | ------ | --------- |
| AUC ROC              | 0.939 | 0.70-0.80 |
| Accuracy             | 0.937 | 85-90%    |
| Precision (loan=yes) | 88.3 | 70-80%    |
| Recall (loan=yes)    | 88.3 | 65-75%    |

## 🖼️ Visual Proof (Add screenshots here)

[Dataset Schema](screenshots/datasetscreenshots/training-progressscreenshots/model-metricsscreenshots/feature-importscreenshots/endpoint-deployscreenshots/sample-predictionan-endpoint-v1
Status: Ready for real-time predictions
Cost: ~$0.50 (free tier credits)
Integration: REST API / Python client

## 💡 Key Learnings (AI Generalist Perspective)
- AutoML auto-handled 10+ categorical features (job, marital, education)
- Feature importance: `housing`, `balance`, `job` (makes banking sense)
- End-to-end production ML in 90 minutes (no coding required)
- Scalable deployment with auto-scaling replicas

## ⏱️ Timeline

Setup + Dataset: 20 min
Training: 60+ min (1 node-hour)
Evaluation + Deploy: 10 min
Portfolio: 10 min
TOTAL: 90+ min

## 🔗 Resources
- [Vertex AI AutoML Docs](https://cloud.google.com/vertex-ai/docs/beginner/beginners-guide) [web:1]
- [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---
**Built by [Luv Saxena] - AI Generalist Portfolio Project**  
*December 2025*
