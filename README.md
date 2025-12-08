# A Post Hoc Explainability Framework for Surface Urban Heat Island Disparities
This repository houses code for the paper *Attributing Marginal Contribution of Biophysical Differences to Neighborhood-Scale Heat Island Disparities with Explainable Machine Learning*.

## Abstract
Numerous local to national scale studies have demonstrated that different population groups in the U.S. have distinct burdens of urban heat. However, these studies have primarily used linear models to map the outcome (generally the urban heat island effect) to its biophysical predictors. To capture non-linear effects of biophysical factors and further attribute them to these disparities, we implement an explainable machine learning approach to study surface urban heat island (SUHI) intensity at the neighborhood scale for all major U.S. urban areas. Similar to prior research, we find that Black and Hispanic people live in neighborhoods with higher SUHI than white people on average, even when accounting for economic factors, which is largely explained by biophysical differences. However, finely disaggregating SHAP (SHapley Additive exPlanations) values across race, socioeconomic indicators, and climate regions, we find that these biophysical factors vary dramatically by demographics nationally. Some patterns still hold from previous studies: the oft-studied vegetation index, is a major driving factor of SUHI disparities for Black and Hispanic residents, especially those who are low income. However, while built-up extent is the second biggest warming factor for Black residents nationally, lower normalized difference built-up index indicators seems to serve a cooling effect for Hispanic residents in urban arid regions. In addition, lower elevation for Hispanic people in arid regions seems to result in a warming effect. Our findings have implications for data-driven, equity-oriented urban and regional policy concerning heat mitigation strategies.

## Data availability
1. The SUE data is available via Zenodo: 
2. The NTL data is available via Harvard Dataverse: https://doi.org/10.7910/DVN/1F72FB

## Running the Code
1. Download the data and place it into the data folder.
2. Pre-process the data as necessary in notebook 0.
3. Run notebooks 1-5. Note that we use Python 3.8.

## Contact 
Correspondence to tc.chakraborty@pnnl.gov
