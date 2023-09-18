# Building-Damage-Grade-Assessment
## Machine Learning Assessment of Damage Grade for Post-Earthquake Buildings: A Three-Stage Approach Directly Handling Categorical Features
## Paper link: https://doi.org/10.3390/su151813847
Abstract: The rapid assessment of post-earthquake building damage for rescue and reconstruction is
a crucial strategy to reduce the enormous number of human casualties and economic losses caused
by earthquakes. Conventional machine learning (ML) approaches for this problem usually employ
one-hot encoding to cope with categorical features, and their overall procedure is neither sufficient
nor comprehensive. Therefore, this study proposed a three-stage approach, which can directly handle
categorical features and enhance the entire methodology of ML applications. In stage I, an integrated
data preprocessing framework involving subjective–objective feature selection was proposed and
performed on a dataset of buildings after the 2015 Gorkha earthquake. In stage II, four machine
learning models, KNN, XGBoost, CatBoost, and LightGBM, were trained and tested on the dataset.
The best model was judged by comprehensive metrics, including the proposed risk coefficient. In
stage III, the feature importance, the relationships between the features and the model’s output,
and the feature interaction effects were investigated by Shapley additive explanations. The results
indicate that the LightGBM model has the best overall performance with the highest accuracy of
0.897, the lowest risk coefficient of 0.042, and the shortest training time of 12.68 s due to its relevant
algorithms for directly tackling categorical features. As for its interpretability, the most important
features are determined, and information on these features’ impacts and interactions is obtained to
improve the reliability of and promote practical engineering applications for the ML models. The
proposed three-stage approach can provide a reference for the overall ML implementation process on
raw datasets for similar problems.
