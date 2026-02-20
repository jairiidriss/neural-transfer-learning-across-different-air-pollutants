# Neural Transfer Learning for Cross-Pollutant Air Pollution Prediction

This repository contains the implementation of the **neural transfer learning framework** proposed in the paper:

> Enhancing air pollution prediction: A neural transfer learning approach across different air pollutants  
> DOI: https://doi.org/10.1016/j.eti.2024.103793  

The objective of this work is to improve **air pollutant concentration prediction** by transferring knowledge learned from one pollutant to another using deep neural network models.

---

## Main Features

- Data preprocessing and normalization  
- Baseline deep learning models for single-pollutant prediction  
- Transfer learning across different air pollutants  
- Fine-tuning strategy for target pollutant prediction  
- Performance comparison with conventional machine learning models  
- Evaluation using regression metrics (MAE, RMSE, R²)

---

## Dataset

The experiments are conducted on air quality monitoring datasets including multiple pollutant concentrations and meteorological variables such as:
## Dataset

This work uses the **Beijing Multi-Site Air Quality** dataset, including measurements from the Aotizhongxin monitoring station.  
The dataset contains hourly concentrations of major pollutants and meteorological variables from 12 sites in Beijing (2013–2017), sourced from the UCI Machine Learning Repository.

**Input variables:**
- PM2.5  
- PM10  
- NO₂  
- SO₂  
- O₃  
- Temperature  
- Humidity  
- Wind speed  

**Target variable:**
- Future concentration of the selected pollutant  

---

## Output

The model produces:

- Predicted pollutant concentration values  
- Performance evaluation metrics  
- Comparative analysis between baseline and transfer learning models  

---

## Reference

If you use this code, please cite the original paper.
