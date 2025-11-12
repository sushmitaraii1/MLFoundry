# 🧱 MLFoundry

> **Forge your own machine learning models - from data to insight.**

MLFoundry is an open-source environment for learning, building, and experimenting with machine learning models.  
It allows users to upload datasets, select algorithms, tune parameters, train interactively, and visualize results, all in one workspace.

---

## 🚀 Features

- 🧩 **Modular Design** - Plug-and-play architecture for adding new models and datasets  
- 📊 **Regression & Classification Support** - Linear, Logistic, Ridge, Lasso, Tree-based, etc.  
- ⚙️ **Interactive Training** - Upload your dataset, choose a model, and train in real time  
- 📈 **Evaluation Dashboard** - Metrics, visualizations, and model comparisons  
- 💾 **Model Export** - Download trained models and reports for reuse  

---

## 📁 Project Structure

```
MLFoundry/
├── datasets/               # Sample datasets
├── mlfoundry/              # Core package
│   ├── models/             # Model definitions
│   ├── pipelines/          # Preprocessing + training
│   ├── evaluation/         # Metrics + visualization
│   ├── utils/              # Helper functions
│   └── ui/                 # Streamlit or FastAPI interface
├── notebooks/              # Exploratory and demo notebooks
├── app.py                  # Entry point for running the app
└── README.md
```


---

## 🧠 Getting Started (Poetry)

### 1) Install Poetry (if not already)
Follow the official installer or:
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

### 2) Create and activate the environment
```bash
poetry install
poetry shell
```

### 3) Run the app
```bash
poetry run streamlit run app.py
```

> Tip: you can exit the virtualenv with `exit` and re-enter later with `poetry shell`.


## 🧩 Roadmap

- [x] Linear & Logistic Regression  
- [x] Ridge and Lasso Regularization  
- [ ] Tree-based Models and Ensembles  
- [ ] SVMs and PCA  
- [ ] Clustering & Dimensionality Reduction  
- [ ] Deep Learning Integration  
- [ ] Cloud Deployment (FastAPI backend)  

---

## 🤝 Contributing

Contributions, feedback, and ideas are welcome!  
If you’re learning or experimenting with ML, feel free to fork the repo, add a new model, or improve documentation.


---

> “From raw data to refined intelligence - MLFoundry is where models are forged.”
