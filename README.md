# ml_fire

## ESoWC 2019 --- Data-driven feature selection towards improving forecast-based prediction of wildfire hazard

__Team:__ [@mariajoaosousa](https://github.com/mariajoaosousa), [@eduardogfma](https://github.com/eduardogfma), [@ricardomaia300](https://github.com/ricardomaia300)

### Summary
This project proposes the application of machine learning techniques for the development of prediction models of extreme fire events, based on the knowledge discovery in databases (KDD) framework. This work aims to devise data-driven feature selection approaches adequate for the calibration of the Canadian Forest Fire Weather Index system, to provide a deeper understanding of the datasets open-sourced by ECMWF / Copernicus.

### Proposed Approach

In this work, we propose following the Knowledge Discovery in Datasets (KDD) framework in order to establish a systematic approach that encompasses the steps illustrated in Fig. 1.

![](https://lh4.googleusercontent.com/SnZsRYDmbDhOLeTC9xQ1DBTS_pK4WWHAk7SbPcJ1dOa0mr_pORSE6n2QaRDH2rsYXhWCMU1hLHZW4bY515pLIbKjHa-7R_diq7mBAadswAFySsKNCbl7TDH8irx8SxX4o_ugHpKAqLeeyxsgBg)
The basis of this process starts with establishing the research topics to be addressed in this investigation. In the context of the prediction of extreme fire events, the nature of different fire regimes influences the spatial occurrence of these phenomena, thus it is important to take into consideration the following modeling assumptions:

-   threshold of fire hazard classes may be different across regions;

-   the most significant variables, i.e. the set of features that yields the best performance in terms of prediction ability may differ across regions.

In that sense, developing machine learning models for this problem requires devising adequate and systematic feature selection techniques for handling data dimensionality and assess the significance of the variables for modeling the problem at hand.
