# HierChangeRatio

These code chunks are used to performe the analysis presented in the paper "Nilsen, E.B. & Strand, O. (2018) *Integrating data from multiple sources for insights into demographic processes: Simulation studies and proof of concept for hierarchical change-in-ratio models* PlosOne". 

- S1 - Includes jags-code to construct models
- S2 - Includes R-code to simulate population dynamocs and observation process
- S3 - Includes code to prepare data and run models
- S4 & S5: Empirical data and metdata
- File "Sensitivity analyses" contains code used to conduct sensitivity analyses asreported in the paper. This code file is not included as appendix in original paper. 

### Abstract: 
*We developed a model for estimating demographic rates and population abundance based on multiple data sets revealing information about population age- and sex structure. Such models have previously been described in the literature as change-in-ratio models, but we extend the applicability of the models by i) using time series data allowing the full temporal dynamics to be modelled, by ii) casting the model in an explicit hierarchical modelling framework, and by iii) estimating parameters based on Bayesian inference. Based on sensitivity analyses we conclude that the approach developed here is able to obtain estimates of demographic rate with high precision whenever unbiased data of population structure are available. Our simulations revealed that this was true also when data on population abundance are not available or not included in the modelling framework. Nevertheless, when data on population structure are biased due to different observability of different age- and sex categories this will affect estimates of all demographic rates. Estimates of population size is particularly sensitive to such biases, whereas demographic rates can be relatively precisely estimated even with biased observation data as long as the bias is not severe. We then use the models to estimate demographic rates and population abundance for two Norwegian reindeer (Rangifer tarandus) populations where age-sex data were available for all harvested animals, and where population structure surveys were carried out in early summer (after calving) and late fall (after hunting season), and population size is counted in winter. We found that demographic rates were similar regardless whether we include population count data in the modelling, but that the estimated population size is affected by this decision. This suggest that monitoring programs that focus on population age- and sex structure will benefit from collecting additional data that allow estimation of observability for different age- and sex classes. In addition, our sensitivity analysis suggests that focusing monitoring towards changes in demographic rates might be more feasible than monitoring abundance in many situations where data on population age- and sex structure can be collected.*    