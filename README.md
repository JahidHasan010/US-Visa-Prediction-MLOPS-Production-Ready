# 🇺ud83c� US Visa Prediction – End-to-End MLOps Pipeline 🚀  

![MLOps Workflow](https://your-image-link.com) <!-- Add an architecture diagram or relevant image -->

## 📌 Project Overview  
This project presents an **end-to-end MLOps pipeline** for predicting **US visa approvals** using machine learning. The pipeline is designed with **scalability, maintainability, and automation** in mind, leveraging best practices in **MLOps, cloud deployment, and CI/CD automation**.  

## 🏠 Key Features  
✅ **Data Ingestion**: Extracting structured data from **MongoDB**  
✅ **Exploratory Data Analysis (EDA)**: Identifying key trends and relationships  
✅ **Feature Engineering**: Creating domain-specific features to enhance model accuracy  
✅ **Model Training & Experiment Tracking**: Using **MLflow** to track hyperparameters & performance  
✅ **Containerization**: Dockerizing the entire pipeline for consistency across environments  
✅ **Model Deployment**: Deploying the trained model on **AWS EC2**  
✅ **CI/CD Integration**: Automating model training & deployment using **GitHub Actions**  
✅ **Cloud Storage & Versioning**: Storing models securely on **AWS S3**  

---

## 📁 Project Structure  
```
us-visa-prediction-mlops/
│── data_ingestion/          # Scripts for fetching data from MongoDB
│── eda/                     # Jupyter notebooks & scripts for EDA
│── feature_engineering/      # Scripts for feature extraction & transformation
│── model_training/           # ML model training scripts with MLflow tracking
│── model_evaluation/         # Performance metrics, validation scripts
│── deployment/               # Deployment scripts using FastAPI & Docker
│── monitoring/               # Model drift & performance monitoring setup
│── ci_cd/                    # GitHub Actions workflows & automation scripts
│── config/                   # Config files for AWS, MLflow, and environment variables
│── requirements.txt          # Python dependencies
│── Dockerfile                # Containerization setup
│── README.md                 # Documentation
│── .github/workflows/        # CI/CD pipeline definitions
│── main.py                   # Main application script
```

---

## 🛠️ Tech Stack  
| Category           | Tools / Frameworks |
|--------------------|-------------------|
| **Programming**   | Python       |
| **Data Storage**  | MongoDB, AWS S3    |
| **ML Frameworks** | Scikit-learn, MLflow |
| **MLOps Tools**   | Docker, GitHub Actions, MLflow |
| **Cloud**         | AWS (EC2, S3, ECR) |
| **Deployment**    | FastAPI    |

---

Experiment tracking was conducted via **MLflow**, and hyperparameter tuning was performed using **GridSearchCV**.

---

## 🚀 Deployment & Usage  

### 🐓 Running with Docker  
```bash
# Build the Docker image
docker build -t us-visa-prediction .

# Run the container
docker run -p 8080:8080 us-visa-prediction
```

---

## 🛍️ CI/CD Pipeline  
The pipeline is fully automated with **GitHub Actions** for CI/CD:  

1. **Code Push → Automatic Build** (Docker + GitHub Actions)  
2. **Model Training & Tracking** (MLflow)  
3. **Model Deployment** (AWS EC2 + S3)  

✅ Every new push to the repository triggers **automated tests, model training, and redeployment**.  

---

## 📌 Challenges & Solutions  
### ❌ Challenge: Data Imbalance  
**Solution**: Applied **SMOTE oversampling** and **class-weight balancing** to handle class imbalances effectively.  

### ❌ Challenge: Model Drift  
**Solution**: Integrated **Evidently AI** for continuous monitoring of data drift and model performance degradation.  

### ❌ Challenge: Deployment Scaling  
**Solution**: Used **AWS EC2 with auto-scaling** and containerized services for efficient production readiness.  

---

## 🎯 Future Improvements  
📌 Enhance the model with **transformer-based architectures (BERT, GPT-4)** for NLP-based visa processing.  
📌 Deploy a **full monitoring dashboard** using **Grafana + Prometheus**.  
📌 Implement **real-time streaming pipeline** using **Apache Kafka**.  

---

## 📜 License  
This project is open-source under the **MIT License**.  

---

## 📩 Contact  
For collaboration or inquiries, feel free to reach out:  

💌 jahidjahid36452@gmail.com  

---

# 🔥 If you find this project useful, don't forget to ⭐ the repo!  
