# Applied-ML-for-accelerated-Scale-up-of-Stirred-Reactors
Develop an ML model to predict the median turbulent dissipation rate (ε_p50) in stirred reactors using CFD-generated data, with validation against a reference study. The workflow covers data cleaning, EDA, feature engineering, pipeline preparation, model execution, and results analysis to ensure robustness and interpretability. https://novalabs.ch/use-case/applying-machine-learning-for-accelerated-scale-up-of-stirred-reactors/

<img width="408" height="173" alt="image" src="https://github.com/user-attachments/assets/e34ec059-be3a-4559-83e3-c921d06036a6" />

<img width="561" height="600" alt="image" src="https://github.com/user-attachments/assets/ced0680d-6775-4d11-adbc-6358761385d9" />

The best model was an FCNN, achieving RMSE = 0.0198 and R² = 0.9616 for ε_p50, outperforming the baseline Random Forest (RMSE = 0.0622, R² = 0.6995). It captured nonlinear relations between geometry and operation. Broad model testing and tuning were key; retaining correlated features improved results. RPM showed higher importance than blade count.

<img width="419" height="889" alt="image" src="https://github.com/user-attachments/assets/503ebe74-14d8-49cd-8704-19e9bb88e006" />

# Add. Diffusion-Reaction CNO Starter

This notebook provides a simple convolutional operator baseline in the spirit of a CNO.

It is not a full research-grade CNO implementation. The goal is to give your repository an approachable, extensible convolution-based operator example beside DeepONet and FNO.
<img width="889" height="390" alt="image" src="https://github.com/user-attachments/assets/c5def5bf-99c3-4bc0-b4a7-c8d2b9fe98dc" />
