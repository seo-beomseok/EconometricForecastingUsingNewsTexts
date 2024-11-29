# Replication package for "Econometric Forecasting Using Ubiquitous News Texts: Text-enhanced Factor Model"

2024-11-29
Beomseok Seo (bsseo@sookmyung.ac.kr)

---
## Overview & contents

This repository contains the replication code used to generate the figures and results presented in the main text of "Econometric Forecasting Using Ubiquitous News Texts: Text-Enhanced Factor Model."

The main contents of this repository are as follows:
- `TFIs.ipynb`: codes for exploratory data analysis of TFIs
- `main.ipynb`: codes for running TFM
- `crnn.ipynb`: codes for running CRNN
- `data/`: folder of raw and external datasets
- `fig/`: folder of generated figures
- `outs/`: folder of generated results

The data descriptions are as follows:
- `SI_month_xxx_2005.xx.xx_2024.xx.xx.csv`: external files (their sources are provided in `TFIs.ipynb`)
- `all_dat_MoM.csv`: dataset transformed in the month-over-month growth rate
- `all_dat_YoY.csv`: dataset transformed in the year-over-year growth rate
- `all_grp.csv`: the factor structure used in TFM
- `macro_feat.csv`: meta-information about official statistics including publication lags
- `lda_prop.csv`: latent Dirichlet allocation (LDA) topic series
- `tfi_nsi_epu.csv`: news sentiment index (NSI) and economic policy uncertainty (EPU) of Korea
- `tfis.csv`: theme frequency indices of 15 sectors

<br>
<p align="center">
  <img src="/fig/tfi_0.png" width="350" />
  <img src="/fig/tfi_12.png" width="350" />
</p>

## Instructions & computational requirements

All file paths are relative to the root directory of this repository. The code is compatible with Google Colab environments and requires Python 3.7 or higher with `pandas` (1.3.5), `matplotlib` (3.5.3), `statsmodels` (0.13.5), `joblib` (1.3.2), `seaborn` (0.12.2), `tensorflow` (2.11.0), `keras` (2.9.0), `absl-py` (2.1.0), `protobuf` (3.20.1), `wrapt` (1.16.0), `opt-einsum` (3.3.0), `astunparse` (1.6.3), `termcolor` (2.3.0), and `flatbuffers` (24.3.25).

A list of dependencies for each notebook is provided within the corresponding `.ipynb` file

## References

Seo, B. 2024+. "Econometric Forecasting Using Ubiquitous News Texts: Text-enhanced Factor Model"

The dynamic AWS web application providing weekly and monthly TFIs can be found at the "<a href=http://54.253.91.228:8050/>Text Indices Hub</a>" via https://seo-beomseok.github.io/

<br>
<p align="center">
  <a href=http://54.253.91.228:8050/>
  <img src="/fig/texthub.png" width="800" />
  </a>
</p>

---
