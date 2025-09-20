# \# \*\*Using Machine learning to assess the impact of 'clean air' interventions on Nitrogen Dioxide (NO₂)\*\*

# "Assessing the impact of interventions (e.g., Clean Air Zones) on NO₂ by building a Random Forest machine learning model. Trained on pre-intervention meteorological and time-based features and used to predict NO₂ as if no intervention occurred, revealing its true effect.

# 

# 





# \*\*DESCRIPTION:\*\*

# 

# This project aims to show the impact of an intervention (such as a Clean Air Zone) on NO₂ by building a Random Forest machine learning model. The model is trained on data prior to the introduction of the intervention- using meteorological variables such as wind speed, wind direction, and temperature, along with time-based features.

# 

# The trained model is then used to predict NO₂ concentrations for after the intervention is introduced to extract NO₂ concentrations as if there had been no intervention introduced. These counterfactual predictions are compared with actual observed values during the intervention period to estimate the change in pollutant levels attributable to the intervention. COVID-19 periods, during which traffic and pollution levels dropped significantly, is disregarded for model training inline literature on the topic.

# 

# This approach is taken for NO₂ analyses as NO₂ concentrations are greatly affected by meteorological variables. This makes NO₂ analysis hard as changes in concentrations are often hidden by meteorological factors. The machine learning model essentially takes out the influence of meteorological variables and makes impacts of interventions easy to analyse.

# 

# This workbook is based off work from my University dissertation project "Using machine learning to assess the impact of Newcastle and Sheffield’s Clean Air Zones on Nitrogen dioxide". This workbook has been adapted from the dissertation so that any intervention on NO₂ can be investigated as long as there is enough DEFRA data available for the site

# 

# \*\*OBJECTIVES:\*\*

# 

# \- Develop a regression-based time series model to predict NO₂ levels using weather and temporal features.

# \- Generate counterfactual pollutant predictions for the post intervention period.

# \- Quantify and visualise the estimated impact of the intervention by comparing predicted (no-intervention) vs actual (with-intervention) values.



