# Keyword Spotting
> This repository includes KWS model experiments.

## Directory Layout
    .
    ├── data                    # saved train-val split
    ├── history                 # saved training logs
    ├── models                  # old models (not used)
    ├── student_models          # distilled models
    ├── KWS.ipynb               # experiments
    ├── base_model.pt           # base model
    ├── kws_experiments.csv     # csv file of experiment results
    └── requirements.txt

## KWS experiments
Shown in `KWS.ipynb` and include:
- Streaming
- Model compression experiments
    - Dark Knowledge Distillation
    - Attention Distillation
    - Dynamic Quantization

## Final Model
    .
    ├── ...
    ├── student_models
    │   ├── ...
    │   └── student_model_kd_16_dkd_16_4.pt
    └── ...
