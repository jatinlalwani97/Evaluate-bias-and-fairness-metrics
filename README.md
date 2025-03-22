# Evaluate bias and fairness metrics

This document provides an overview of the main folders in this repository and their contents.

## Folders

### EN
The EN folder contains English language resources and data used in our main experiments. This includes prompt templates, response collections, and analysis specific to English language testing.

### AR
The AR folder contains Arabic language resources and data used in our bias analysis experiments. These files support multilingual testing to evaluate how language influences geographical representation in LLM outputs.

### SP
The SP folder contains Spanish language resources and prompts used in our multilingual testing to evaluate how language influences geographical representation in LLM outputs.

### BLS
The BLS (Bureau of Labor Statistics) folder contains occupational data and statistics used as reference points for comparing model outputs against real-world workforce demographics. This data helps evaluate the extent to which model biases align with or diverge from actual workforce composition.

### CrowsPairs
This folder contains resources related to the CrowS-Pairs dataset, which is used as a supplementary experiment for evaluating stereotypical biases in language models. This dataset helps measure bias through metrics like demographic parity and equality of odds.

### Data
The Data folder serves as the central repository for our primary datasets, including:
- Human perception datasets for occupational stereotypes, processed occupation data classified as "Female-Stereotyped", "Male-Stereotyped", or "Gender-Neutral"
- CrowsPair Modified prompts
- BLS Dataset

## Results 
- The outputs are also stored in each folder of EN, SP, and AR

## Usage

Each folder contains specific data and resources that support different aspects of our bias and fairness evaluation methodology. The primary workflow involves:

1. Using occupation data from the Data folder
2. Running experiments with prompts from the EN, SP, and AR folders
3. Comparing results against reference data in the BLS folder
4. Conducting supplementary analysis using the CrowsPairs dataset
5. Storing and analyzing results in the Data folder

## Additional Information

For more details on the specific contents of each folder and how they relate to the experimental methodology described in our paper, please refer to the README files within each directory.
