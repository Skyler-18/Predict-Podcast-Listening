# 🎧 Podcast Listening Time Predictor

**Goal:**  
Predict how long users will listen to a podcast episode using features like host/guest popularity, episode length, sentiment, genre, and ad placements.

## 🚀 Business Use-Case
Podcast platforms can:
- Optimize ad placement & episode duration.
- Improve personalization & recommendations.
- Identify content that maximizes user retention.

## 📁 Project Structure (Modular)
Follows a production-grade ML architecture using Cookiecutter ML Template.

## 🔧 Tech Stack
- **ML**: scikit-learn, XGBoost, SHAP
- **Tracking**: DVC, MLflow
- **Deployment**: Streamlit / React + FastAPI, Docker
- **CI/CD**: GitHub Actions
- **Monitoring**: Model drift + performance logs

## 🧪 ML Tasks
- Data Preprocessing
- Feature Engineering
- Model Training + Evaluation
- Experiment Tracking
- CI/CD + Testing
- Deployment
- Model Monitoring

## 💡 Outcome
An end-to-end ML system that predicts podcast listening time and integrates data, modeling, deployment, and business impact — ready for real-world use.

## 🛠 Usage (Planned)
```bash
make train           # Train pipeline
make evaluate        # Evaluate model
make deploy          # Deploy locally
make test            # Run unit tests
```

## 📌 Upcoming Features
- Streamlit frontend MVP
- React + FastAPI production version
- CI/CD pipelines
- Docker deployment