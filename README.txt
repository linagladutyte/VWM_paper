These scripts were written to pre-process and analyze data described in “Exploring the role of sex, sex steroids, menstrual cycle, and hormonal contraception use in visual working memory: Insights from behavioral and EEG analyses” by Gaižauskaitė et al. (2025) (https://doi.org/10.1016/j.ijpsycho.2025.112520).  

The 1_demographic directory contains a markdown script for analyzing group differences and visualizations for demographic, questionnaire, and hormonal variables, as well as their correlations with each other and cognitive performance. Data with variables is also available in this directory.  

2_behavioral contains raw behavioral data, scripts for calculating behavioral parameters (response time, performance accuracy, and memory capacity), and statistical analyses.  

EEG data were preprocessed using EEGLAB v2020.1 in MATLAB R2022b with the Darbeliai v2022.12.22.1 toolbox (https://github.com/embar-/eeglab_darbeliai/blob/master/README.txt), which features a drop-down menu interface.  

ERPs were extracted from PO7/PO8 electrodes for each of the four (3 RVF, 3 LVF, 4 RVF, 4 LVF) conditions using MATLAB, with further analysis conducted in Python (version 3.11.8) and R (v4.3.2). Extracted ERP data is available in the 3_CDA directory, which also contains scripts for CDA extraction, descriptive statistics and visualizations, and statistical analyses for extracted CDA amplitude.  

The 4_additional_analyses directory includes a script comparing task performance, capacity, and CDA amplitudes between females using OCs with androgenic vs. anti-androgenic progestins and higher vs. lower ethinyl estradiol doses. Data to be used can be found in 1_demographic.  

For a more detailed explanation of the analysis steps, see the paper mentioned above.

