# Course- Machine Learning for Materials Engineering

# AMP-PCS dataset
-----
The Name of our project stands for **A**ccreting **M**illisecond **P**ulsars - **P**olarization via **C**ompton **S**cattering.
Simplified analysis with a focus on 5 X-features(Te, Tbb, τT , E, μ) and 2 Y -labels (I & U Stokes Parameters), laying the groundwork for complex hyperparameter adjustments and advanced modeling in later stages
Used Modeling Techniques:
• KRR Regression Analysis: To predict continuous output values (Stokes
parameters) based on neutron star parameters.
• Random Forest
• XGBoost (eXtreme Gradient Boosting)
• KRR
• Multilayer Perceptron:
(I) Neural networks for complex pattern recognition and
high-dimensional data analysis.
(II) Suitable for capturing non-linear relationships in the data. 

Our Best results were obtained by Kernel Ridge regression and it was the easiest to optimize. Our model underwent rigorous testing on a 30k-size dataset,
showcasing its robust performance.

Project is based on the following publication:
"Polarized radiation from an accretion shock in accreting millisecond pulsars using exact Compton scattering formalism", Anna Bobrikowa et al. Astronomy and Astrophysics, 678, 2023, https://arxiv.org/abs/2309.0232.

Associated dataset can be found here:
[AnnaBobrikowa/ComptonSlabTables](https://github.com/AnnaBobrikova/ComptonSlabTables)
