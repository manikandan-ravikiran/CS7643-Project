# CS7643-Project
The is the repository for the final Project of CS7643 (Spring 2022). The repository is organized as follows

```bash
├── code
│   ├── data_creator
│   │   └── TLA_Data_Prep.ipynb  --> This is used for preparation of data for TLA model.
│   ├── evaluator
│   │   ├── BIO_data_creator.ipynb --> This is used to create BIO encoded data suitable for training different transformers.
│   │   ├── LIG Evaluator.ipynb --> This is used to evaluate IG models under ZSA architecture
│   │   ├── lime_evaluator.ipynb --> This is used to evaluate LIME models under ZSA architecture
│   │   └── NER Evaluator.ipynb --> This is used to evaluate NER models under ZSA architecture
│   ├── trainers
│   │   ├── TLA_trainer.ipynb --> This is used to train the sequence labeling transformers under TLA architecture.
│   │   ├── zsa_augmentation_trainer.ipynb --> Used to train different ZSA transformers with data augmentation training.
│   │   ├── zsa_multilabel_trainer.ipynb --> Used to train different ZSA transformers with multilabel training.
│   │   └── zsa_trainer.ipynb --> Used to train baseline ZSA transformers with DOSA dataset.
│   └── zsa_inference --> This isrepository modified from TranSHAP library for GPU inference on LIME and SHAP.
│       ├── data.csv
│       ├── example_visualization.py
│       ├── explainers
│       │   ├── IME_for_text.py
│       │   ├── __init__.py
│       │   ├── LIME_for_text.py
│       │   ├── __pycache__
│       │   │   ├── __init__.cpython-37.pyc
│       │   │   ├── SHAP_for_text.cpython-37.pyc
│       │   │   └── visualize_explanations.cpython-37.pyc
│       │   ├── SHAP_for_text.py
│       │   └── visualize_explanations.py
│       ├── figures
│       │   ├── figure_transshap.png
│       │   ├── lime_neg.png
│       │   ├── lime_pos.png
│       │   ├── shap_neg.png
│       │   ├── shap_pos.png
│       │   ├── visualize_expl_new.png
│       │   └── visualize_expl.png
│       ├── LICENSE
│       ├── README.md
│       ├── requirements.txt
│       ├── run.py
│       └── shap_explainer.ipynb
├── data --> This contains all the data used in the research activity.
│   ├── DOSA
│   │   ├── test.tsv
│   │   └── train.tsv
│   ├── DOSA_MAD
│   │   └── train.tsv
│   ├── DOSA_MID
│   │   └── train.tsv
│   └── TLA_DOSA
│       ├── test_ner.tsv
│       └── train_ner.tsv
├── LICENSE
├── models --> This contains all the key models developed in this work. For inference the models are to be used with respective inference scripts.
│   └── readme.md
└── README.md
```

