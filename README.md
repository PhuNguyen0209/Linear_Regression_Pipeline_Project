# MLproject — End-to-End ML Score Prediction with Linear Regression, Flask

[![Python](https://img.shields.io/badge/python-3.10%2B-informational.svg)]()  
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]()

This project demonstrates how to build, package, and serve a machine learning model using **Flask** for deployment. It covers the complete lifecycle from **data ingestion and preprocessing**, through **model training and artifact management**, to exposing predictions via a **web interface and REST API**.

The project structure is modular and designed with **production best practices** in mind, so it can serve as both a **learning template** and a foundation for real applications.

---

## ✨ Features

- **Modular ML Pipeline**  
  Clear separation of concerns: data preprocessing, model training, and prediction are implemented in `src/`.

- **Web Deployment with Flask**  
  Users can interact with the model either through a web form (`templates/`) or via JSON API requests.

- **Artifact Management**  
  Trained models, preprocessors, and encoders are stored in the `artifacts/` directory for reproducibility.

- **Extensible Design**  
  Adding new features or swapping in new models only requires changes inside `src/` without breaking the Flask app.

- **Documentation First**  
  Model card, API specification, architecture diagram, and runbook included in `docs/` for professional project hygiene.

---

## 🚀 Quickstart

### 1. Clone the repository

```bash
git clone https://github.com/PhuNguyen0209/MLproject.git
cd MLproject
```

## 📁 Project Structure

.
├─ app.py # Flask app entrypoint
├─ src/ # Core ML pipeline modules
│ ├─ pipeline/ # Data transformation, training, prediction pipeline
│ ├─ utils/ # Helper utilities (logging, file I/O, validation)
│ └─ init.py
├─ templates/ # HTML templates for Flask front-end
├─ artifacts/ # Trained models, preprocessors, encoders
├─ docs/ # Documentation (model card, API spec, runbook, etc.)
├─ tests/ # Unit tests (optional)
├─ requirements.txt # Python dependencies
├─ setup.py # Project metadata for packaging
├─ .gitignore # Ignored files for git
└─ README.md # Project documentation

```

```
