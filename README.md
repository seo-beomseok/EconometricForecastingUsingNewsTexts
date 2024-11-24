# Replication package for "Econometric Forecasting Using Ubiquitous News Texts: Text-enhanced Factor Model"

2024-11-22
Beomseok Seo (bsseo@sookmyung.ac.kr)

---
## Overview & contents

This repository provides replication codes for generating figures and results in the main texts of "Econometric Forecasting Using Ubiquitous News Texts: Text-enhanced Factor Model"

The main contents of this repository are as follows:
- `TFIs.ipynb`: codes for exploratory analysis of TFIs
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

## Instructions & computational requirements

All file paths are relative to the root of this repository. All codes are runnable in Google colab environments and Python 3.7.

The lists of dependent packages can be found in each `.ipynb` file.

## References

Seo, B. 2024+. "Econometric Forecasting Using Ubiquitous News Texts: Text-enhanced Factor Model"

The dynamic AWS web application providing TFIs can be found in "Text Indices Hub" at https://seo-beomseok.github.io/

<br>
<p align="center">
  <img src="/fig/news_survey.png" width="500" />
</p>

<p align="center">
  <img src="/fig/tfi_0.png" width="300" />
  <img src="/fig/tfi_12.png" width="300" /> 
</p>
