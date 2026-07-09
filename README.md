# 🇲🇽 PIB per Cápita Estatal — México (2006–2023)

Modelo predictivo de Machine Learning para predecir el PIB per cápita por entidad federativa en México, identificando qué variables socioeconómicas influyen más en el desarrollo económico estatal.

## Quick Links
[Presentación](https://canva.link/486t5iuvv8ko186)
[Notebook Pipeline](https://github.com/ledtorres/Pipeline-de-predicci-n-del-PIB-per-c-pita-de-M-xico-2006-2023-/blob/main/notebooks/Pipeline_PIB_per_capita.ipynb)
[Notebook Merge](https://github.com/ledtorres/Pipeline-de-predicci-n-del-PIB-per-c-pita-de-M-xico-2006-2023-/blob/main/notebooks/Merge_Dataset_Pipeline_PIB_per_capita.ipynb)
[Dataset]()

## Key Insights
- Escolaridad promedio y % sector secundario son los principales determinantes del PIB per cápita estatal
- Random Forest superó a XGBoost, Ridge y Stacking con R²=0.908
- El COVID-19 generó un shock no anticipado en 2020 para todos los modelos
- Edomex es el estado más difícil de predecir por su población masiva vs PIB per cápita bajo

## Tech Stack
- Python: Pandas, Matplotlib, Seaborn, Sklearn, Xgboost.
- Canva (Presentación)
- Fuentes: INEGI, CONAPO, Banxico, SE, SESNSP
