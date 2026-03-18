# HealthCare — AI-Powered Multi-Disease Diagnosis Platform

> Multi-modal AI system for early disease detection using Machine Learning and Deep Learning  
> `Python` `TensorFlow` `PyTorch` `scikit-learn` `Flask` `React` `CNN` `SVM` `Random Forest`

---

## 🎯 Problem

Early screening for heart disease, diabetes, and pneumonia requires specialist access, expensive tests, and significant time — making it inaccessible at scale. This platform brings AI-assisted screening to structured patient data and medical images.

---

## 💡 Solution

A unified diagnosis platform covering 3 disease domains from a single system:

| Disease | Input Type | Model |
|---|---|---|
| Heart Disease | Structured patient data | SVM / Logistic Regression / Random Forest |
| Diabetes | Structured patient data | SVM / Logistic Regression / Random Forest |
| Pneumonia | Chest X-ray images | CNN (TensorFlow / PyTorch) |

---

## 🏗️ Architecture

```
┌─────────────────────┐       ┌──────────────────────────┐
│   React Frontend    │ ────▶ │   Flask / Django REST API │
│  HTML · CSS · Boot  │       │   (ML Backend)            │
└─────────────────────┘       └──────────┬───────────────┘
                                         │
                    ┌────────────────────┼───────────────────┐
                    ▼                    ▼                   ▼
           Heart / Diabetes         Pneumonia            User Data
           scikit-learn models      CNN Model            Secure Storage
           (SVM, LR, RF)           (TF / PyTorch)
```

- **Decoupled architecture** — ML backend and frontend scale independently
- **RESTful API** — clean separation between prediction logic and UI
- **Secure storage** — user data and prediction history stored safely

---

## 🔬 Model Details

### Structured Data (Heart Disease & Diabetes)
- Benchmarked 3 classifiers: Logistic Regression, SVM, Random Forest
- Selected best-performing model per disease domain based on evaluation metrics
- Features engineered from clinical parameters

### Image Data (Pneumonia)
- CNN architecture trained on chest X-ray dataset
- Implemented in both TensorFlow and PyTorch
- Binary classification: Normal vs Pneumonia

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Deep Learning | TensorFlow · PyTorch |
| ML | scikit-learn |
| Backend | Flask · Django · REST API |
| Frontend | React · Bootstrap · HTML · CSS |
| Data Processing | Pandas · NumPy |
| Visualization | Matplotlib |

---

## 🚀 Getting Started

```bash

1. Install Anaconda
2. Download Project Zip or Clone Project Git Repo
3. Open Full Project Folder on VS code 
4. In VS Code Open cmd(CTRL + J) (note : By default open PowerShell so first change PowerShell to cmd)
5. In cmd enter the command that below mention:
	1. conda create --name healthcure python=3.9
		in that ask y/n in that gives : y
	2. conda activate healthcure
	3. pip install -r requirements.txt
	4. python app.py
Terminate Project:
6. conda deactivate
```

---

## 🎯 Use Cases
- Early health screening
- Telemedicine platforms
- Clinical decision support tools

---

## 👤 Author
✨ **Aryan Rajyaguru** - [GitHub](https://github.com/aryanrajyaguru22)</br >
✨ **Princy Patel** - [GitHub](https://github.com/Princy9114)</br >
✨ **Mahek Patel** - [GitHub](https://github.com/MahekPatel11)</br >
✨ **Umang Jadeja** - [GitHub](https://github.com/umang2640)</br >
