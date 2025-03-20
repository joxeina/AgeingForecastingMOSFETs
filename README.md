# Ageing Forecasting MOSFETs
This repository contains the code of the paper "Comparative Analysis and Evaluation of Aging Forecasting Methods for Semiconductor Devices in Online Health Monitoring" by Adrian Villalobos (Mondragon University, Spain), Iban Barrutia (Mondragon University, Spain), Rafael Peña-Alzola (University of Strathclyde, UK), Tomislav Dragicevic (DTU - Technical University of Denmark), and Jose I. Aizpurua (University of the Basque Country and Ikerbasque Basque Foundation for Science, Spain), published in Engineering Applications of Artificial Intelligence.

The analysis is based on the NASA's MOSFET dataset [1]. The Code folder includes Jupyter Notebooks with (i) short-term Temporal Fusion Transformer (TFT) experiments (ii) long-term Temporal Fusion Transformer (TFT) experiments (leave one out) and (iii) extraction of explainability features and attention points from the TFT.

[1] J. Celaya et al. "MOSFET Thermal Overstress Aging Data Set". In: NASA AMES Prognostics Data Repository (2007). URL: https://www.nasa.gov/intelligent-systems-division/discovery-and-systemshealth/pcoe/pcoe-data-set-repository/


# How to cite

Villalobos, A., Barrutia, I., Peña-Alzola, R., Dragicevic, T., & Aizpurua, J. I. (2025). Comparative analysis and evaluation of ageing forecasting methods for semiconductor devices in online health monitoring. Engineering Applications of Artificial Intelligence. https://doi.org/10.1016/j.engappai.2025.110545

Please click on the "" button on the right side to generate the bibtex file.

Adrian Villalobos, Iban Barrutia, Rafael Peña-Alzola, Tomislav Dragicevic, Jose I. Aizpurua,
Comparative analysis and evaluation of ageing forecasting methods for semiconductor devices in online health monitoring,
Engineering Applications of Artificial Intelligence,
Volume 150,
2025,
110545,
ISSN 0952-1976,
https://doi.org/10.1016/j.engappai.2025.110545.
(https://www.sciencedirect.com/science/article/pii/S0952197625005457)
Abstract: Semiconductor devices, especially MOSFETs (Metal–oxide–semiconductor field-effect transistor), are crucial in power electronics, but their reliability is affected by ageing processes influenced by cycling and temperature. The primary ageing mechanism in discrete semiconductors and power modules is the bond wire lift-off, caused by crack growth due to thermal fatigue. The process is empirically characterized by exponential growth and an abrupt end of life, making long-term ageing forecasts challenging. This research presents a comprehensive comparative assessment of different forecasting methods for MOSFET failure forecasting applications. Classical tracking, statistical forecasting and Neural Network (NN) based forecasting models are implemented along with novel Temporal Fusion Transformers (TFTs). A comprehensive comparison is performed assessing their MOSFET ageing forecasting ability for different forecasting horizons. For short-term predictions, all algorithms result in acceptable results, with the best results produced by classical NN forecasting models at the expense of higher computations. For long-term forecasting, only the TFT is able to produce valid outcomes owing to the ability to integrate covariates from the expected future conditions. Additionally, TFT attention points identify key ageing turning points, which indicate new failure modes or accelerated ageing phases.
Keywords: Semiconductor; Prognostics; Forecasting; Condition monitoring; Temporal Fusion Transformer; Neural Networks

