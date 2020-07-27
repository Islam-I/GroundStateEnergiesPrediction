# Ground State Energies Prediction

## This project is part of Physics department graduation report.

The purpose of this project is to use machine learning methods to come up with a model that can predict molecular properties from a database of simulations.

Here I used:

    Linear-based models: Lasso, Ridge, and ElasticNet.

    Tree-based models: Random Forest, LightGBM, XGBoost, and Averaged model of XGBoost and LightGBM.

    K-nearest neighbors model.

The [data](https://www.kaggle.com/burakhmmtgl/energy-molecule) is used for a [publication](https://aip.scitation.org/doi/10.1063/1.4964093) in Journal of Chemical Physics.

The used data is CSV file consists of 16242 entries and 1277 columns. The first 1275 columns are entries in the Coulomb matrix that act as molecular features. The 1276th column is the Pubchem Id --will be removed in the analysis-- where the molecular structures are obtained. The 1277th column is the atomization energy calculated by simulations using the Quantum Espresso package.
