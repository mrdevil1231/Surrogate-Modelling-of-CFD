# Surrogate-Modelling-of-CFD

CFD (Computational Fluid Dynamics) deals with the study of fluid flow around solid bodies. In this project, aerodynamic data for 4-digit NACA airfoils was extracted to obtain inputs along with corresponding lift (Cl) and drag (Cd) coefficients. Data normalization techniques were applied to reduce skewness and improve model generalization. Four models—Linear Regression, Ridge Regression, Neural Network, and Random Forest—were trained to capture aerodynamic patterns, and their performances were compared through parameter tuning and accuracy evaluation.

Unlike traditional CFD simulations, which are computationally intensive and time-consuming, this machine learning approach enables rapid prediction of aerodynamic coefficients once trained. It offers a cost-effective and efficient alternative for preliminary airfoil analysis, especially when dealing with large datasets or requiring real-time performance insight.
