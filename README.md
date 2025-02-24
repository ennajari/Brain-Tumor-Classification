# Brain-Tumor-Classification
brain_tumor_project/
│
├── data/
│   ├── Training/          # Vos données d'entraînement actuelles
│   │   ├── glioma/
│   │   ├── meningioma/
│   │   ├── notumor/
│   │   └── pituitary/
│   │
│   └── Testing/           # Vos données de test actuelles
│       ├── glioma/
│       ├── meningioma/
│       ├── notumor/
│       └── pituitary/
│
├── notebooks/
│   ├── 01_exploration.ipynb        # Analyse exploratoire des données
│   ├── 02_preprocessing.ipynb      # Prétraitement des images
│   ├── 03_model_training.ipynb     # Entraînement du modèle
│   └── 04_evaluation.ipynb         # Évaluation du modèle
│
├── saved_models/                   # Pour sauvegarder vos modèles entraînés
│   └── best_model.h5
│
└── results/                        # Pour sauvegarder vos résultats
    ├── plots/                      # Graphiques et visualisations
    └── metrics/                    # Métriques d'évaluation