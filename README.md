# vertex-ai-bank-loan-predictor
No-code Vertex AI AutoML model predicts bank customer housing loans from UCI dataset.
# Bank Housing Loan Prediction with Vertex AI AutoML 🚀

[![Model deployed](screenshots/endpoint-success.png)]

**90-minute no-code ML project: Trained, evaluated, and deployed loan predictor using Google Vertex AI AutoML**

## 📊 Business Problem
Predict active housing loans (`loan: yes/no`) to segment customers for targeted offers.

## 🔧 Tech Stack
- **Platform**: Google Cloud Vertex AI AutoML Tabular
- **Dataset**: UCI Bank Marketing (45k rows × 17 cols) [file:115]
- **Target**: `loan` column (binary classification)

## 📈 Results
| Metric | Value |
|--------|-------|
| AUC ROC | [FILL] |
| Accuracy | [FILL] |
| Precision | [FILL] |
| Recall | [FILL] |

## 🖼️ Screenshots
![Dataset](screenshots/dataset.png)
![Training](screenshots/training.png)
![Metrics](screenshots/metrics.png)
![Endpoint](screenshots/endpoint.png)

## 🚀 Live Demo
Endpoint: `bank-loan-endpoint-v1`

## Key Learnings
- AutoML auto-handled 10+ categorical features
- Training cost: ~$0.50 (free tier)
- Production-ready deployment in <2 min

## Training Timeline
- Dataset: 45,211 rows × 17 columns
- Training time: [X hours] on 1 node-hour budget
- Cost: ~$0.50 (covered by free credits) [web:15]

## Expected Metrics (Bank Loan Prediction)
Typical results for this dataset:
- AUC ROC: 0.70-0.80 
- Accuracy: 85-90%
- Key features: housing, balance, job [file:115]

---
**Built as AI generalist portfolio project in 90 minutes** [memory:21]
