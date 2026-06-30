# Metastability-from-Recurrence-Analysis-in-Depression

## About the Project
This study investigates recurrent patterns in Ecological Momentary Assessment (EMA) data from a single-case longitudinal study (239 days) of a patient diagnosed with major depressive disorder undergoing antidepressant dosage adjustments. We construct a dynamic network based on the synchrony in the rate of change of questionnaire items. Furthermore, we quantify quasi-stationary regions—defined as *metastates*—for individual items using recurrence quantification analysis and Markovian optimization. 

Our results show that an abrupt increase in the average degree of the network, together with a decrease in the correlation between node degree and the number of metastable states, precedes the depressive transition identified by the mean SCL-90 score. These results highlight the potential of Recurrence Plots to map the complex landscape of psychological states, providing a robust framework for quantifying stability and change in high-frequency longitudinal assessments.

---

## Repository Structure
Following open science and reproducible research principles, the repository is structured as follows:

* **`Code/`**: Contains the Python scripts used for data preprocessing, recurrence quantification analysis (RQA), and network metrics computation.
* **`Data/`**: Contains exclusively the final processed version of the dataset used to generate the numerical results presented in the manuscript.
* **`README.md`**: This file, providing a general overview, directory structure, and data attribution.

---

## Data Attribution & Availability
The raw longitudinal data and codebook used in this analysis belong to a third-party study and are distributed under the terms of the **CC-BY License**. To respect copyright and attribution guidelines, the full raw dataset is not re-hosted here.

* **Original Data Repository**: The complete raw data can be accessed via OSF at [https://osf.io/j4fg8/](https://osf.io/j4fg8/).
* **Data Citation**: 
    > Kossakowski, J. J., Groot, P. C., Haslbeck, J. M. B., Borsboom, D., & Wichers, M. (2017). Data from ‘Critical Slowing Down as a Personalized Early Warning Signal for Depression’. *Journal of Open Psychology Data*, 5(1), 1.
