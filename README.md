# **Using Machine learning to assess the impact of 'clean air' interventions on Nitrogen Dioxide (NO₂)**
"Assessing the impact of interventions (e.g., Clean Air Zones) on NO₂ by building a Random Forest machine learning model. Trained on pre-intervention meteorological and time-based features and used to predict NO₂ as if no intervention occurred, revealing its true effect.




**DESCRIPTION:**

This project aims to show the impact of an intervention (such as a Clean Air Zone) on NO₂ by building a Random Forest machine learning model. The model is trained on data prior to the introduction of the intervention- using meteorological variables such as wind speed, wind direction, and temperature, along with time-based features.

The trained model is then used to predict NO₂ concentrations for after the intervention is introduced to extract NO₂ concentrations as if there had been no intervention introduced. These counterfactual predictions are compared with actual observed values during the intervention period to estimate the change in pollutant levels attributable to the intervention. COVID-19 periods, during which traffic and pollution levels dropped significantly, is disregarded for model training inline literature on the topic.

This approach is taken for NO₂ analyses as NO₂ concentrations are greatly affected by meteorological variables. This makes NO₂ analysis hard as changes in concentrations are often hidden by meteorological factors. The machine learning model essentially takes out the influence of meteorological variables and makes impacts of interventions easy to analyse.

This workbook is based off work from my University dissertation project "Using machine learning to assess the impact of Newcastle and Sheffield’s Clean Air Zones on Nitrogen dioxide". This workbook has been adapted from the dissertation so that any intervention on NO₂ can be investigated as long as there is enough DEFRA data available for the site

**OBJECTIVES:**

- Develop a regression-based time series model to predict NO₂ levels using weather and temporal features.
- Generate counterfactual pollutant predictions for the post intervention period.
- Quantify and visualise the estimated impact of the intervention by comparing predicted (no-intervention) vs actual (with-intervention) values.

## Notebooks

| Notebook | Open in Colab | Open on GitHub |
|----------|---------------|----------------|
| Template Cleaned Code | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O-G9VhI721A6IO9gJIsorUljvI3u6r_5) | [View Notebook](https://github.com/HarryPurcell1/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide/blob/main/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide.ipynb) |
| Newcastle Centre Example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17FDUlaGye5HtMUU1qrxPVPkYZ0dyOSue) | [View Notebook](https://github.com/HarryPurcell1/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide/blob/main/Newcastle_Centre_Example.ipynb) |
| Newcastle Cradlewell Example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j-Iw61lS0-cL7cMWx2CnSiweaFHkgBqb) | [View Notebook](https://github.com/HarryPurcell1/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide/blob/main/Newcastle_Cradlewell_Example.ipynb) |
| Sheffield Devonshire Green Example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JRYNYeQ289_7EOcqlwkU9w3jG_QfPDgx) | [View Notebook](https://github.com/HarryPurcell1/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide/blob/main/Sheffield_Devonshire_Green_Example.ipynb) |
| Sheffield Tinsley Example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1753GtVdwnzIRrFkTxiNNM9zQeuYXaX38) | [View Notebook](https://github.com/HarryPurcell1/Using_Machine_learning_to_assess_the_impact_of_clean_air_interventions_on_Nitrogen_Dioxide/blob/main/Sheffield_Tinsley_Example.ipynb) |

## Example Output

Here is an example output from the analysis:

<img width="1229" height="655" alt="shfT" src="https://github.com/user-attachments/assets/4c0f43e2-1253-4fce-a36f-f55971e416aa" />
