# Urban-AI-2025-Contest

This repository is intended to provide instructions to replicate results for the [Urban AI 2025 Contest](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/UrbanAI&referrer=%5BHomepage%5D(%2F)#tab-recent-activity) submission "XGBoost with physics-informed features and residual
regressor for the SBCS benchmark" (submission link provided once available).

**Instructions:**

The files are located in the 'src' folder. To replicate the results, please download the 'main.ipynb' notebook and the '.pkl' model in the same folder (after unzipping the 'physics_informed_models_new_version_compressed.pkl.gz' file). To reproduce the main and ensemble results, please run the last cell of the notebook. To reproduce the plots or the entire workflow, please run the cells above. The 'other.ipynb' contains initial analysis, including the reproduction of the adjacent room layout.

**Reproducibility:**

The code runs the XGBoost models with a compatible NVIDIA GPU using the 'cuda' toolkit. This can be reproduced in GoogleColab with sufficient GPU credits. The reproduction cell with the full results takes approximately 20 minutes to run. The entire workflow with hyperparameter search takes more than 10 hours to run. If GPU is not supported, both reproductions would take longer periods. 

<sub>*The code has been modified and written with the assistance of Claude Sonnet 4. Idea initialization, conceptualization, methodology development, investigation, and writing have been done without assistance.</sub>
