# AI-Radiomics-Carotid

## Overview
This repository contains the code and resources for the project aimed at enhancing cardiovascular risk prediction by analyzing carotid plaque radiomics data. The project leverages advanced machine learning techniques to uncover critical variable interdependencies.

## Project Structure
The repository is organized into several Jupyter notebooks, each focusing on different features and combinations of features used in the analysis:

### Notebooks
1. **AllFeatures.ipynb**
   - This notebook integrates all available features, including clinical history, imaging, and radiomics data, to build comprehensive predictive models.

2. **ClinHistAndImaging.ipynb**
   - This notebook focuses on the combination of clinical history and imaging data, exploring their collective impact on cardiovascular risk prediction.

3. **ClinHistOnly.ipynb**
   - This notebook uses only clinical history data to predict cardiovascular risk, providing a baseline for comparison with other feature sets.

4. **ImagingOnly.ipynb**
   - This notebook utilizes only imaging data to build predictive models, examining the standalone power of imaging features.

5. **RadiomicsAndClinHist.ipynb**
   - This notebook combines radiomics and clinical history data, investigating the synergistic effects of these two feature sets on risk prediction.

6. **RadiomicsAndImaging.ipynb**
   - This notebook merges radiomics and imaging data, aiming to enhance predictive accuracy by leveraging detailed plaque characteristics and imaging information.

7. **RadiomicsOnly.ipynb**
   - This notebook focuses exclusively on radiomics data, analyzing its capability to predict cardiovascular risk independently.

## Getting Started
To get started with the project, clone the repository and open the notebooks in Jupyter Notebook or JupyterLab.

```bash
git clone https://github.com/yourusername/AI-Radiomics-Carotid.git
cd AI-Radiomics-Carotid
