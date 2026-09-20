[README.md](https://github.com/user-attachments/files/32436379/README.md)
# Project 1 — TimesFM 2.5 Forecasting

A portfolio-ready TimesFM 2.5 forecasting project using Google's
`TimesFM_2p5_200M_torch` checkpoint.

## Core model

- TimesFM 2.5
- 200M parameter PyTorch checkpoint
- `google/timesfm-2.5-200m-pytorch`
- Configurable context and forecast horizon
- Continuous quantile head
- Input normalization
- Positive-output inference
- Quantile-crossing correction

## Workflow

Input data → configurable historical window → TimesFM 2.5 → forecast →
forecast table / visualization.

