# Evaluate bias and fairness metrics

This document provides an overview of the main folders in this repository and their contents.

## Folders

### EN
The EN folder contains 3 subfolders for each model (ChatGPT, Gemini, and others), the results are also stored in each subfolder as "llm_cv_summaries_raw" and "llm_cv_summaries_analyzed" CSV, with a map that represents the Geographical distribution of the Engilsh prompts. 

### AR
The AR folder contains the code base and the results of running it with Gemini models, the results are also stored in the folder as "llm_cv_summaries_raw" and "llm_cv_summaries_analyzed" CSV, in addition to a map that represents the Geographical distribution of the Arabic prompts. 

### SP
The SP folder contains the code base and the results of running it with Gemini models, the results are also stored in the folder as "llm_cv_summaries_raw" and "llm_cv_summaries_analyzed" CSV, in addition to a map that represents the Geographical distribution of the Spanish prompts. 

### BLS
This folder contains the code base of this usecase (the dataset can be found in the Data folder) with the results of this experiment. 

### CrowsPairs
This folder contains the base code of our supplementary experiment combined with the results.

### Data
The Data folder serves as the central repository for our primary datasets, including:
- Human perception datasets for occupational stereotypes, processed occupation data classified as "Female-Stereotyped", "Male-Stereotyped", or "Gender-Neutral"
- CrowsPair Modified prompts
- BLS Dataset
- 
### Report
This folder contains the paper and the presentation of our research.


## Usage
Each folder contains specific data and resources that support different aspects of our bias and fairness evaluation methodology. The primary workflow involves:

1. Using occupation data from the Data folder
2. Running experiments with prompts from the EN, SP, and AR folders (API KEYs are needed)
3. Comparing results against reference data
4. Conducting supplementary analysis using the CrowsPairs dataset
5. Storing and analyzing results in each Model Folder
