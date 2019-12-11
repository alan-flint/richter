# richter
Classifying Damage Grade of Buildings from Nepal Earthquake 2015

A machine learning competition from drivendata.org:
https://www.drivendata.org/competitions/57/nepal-earthquake/page/134/

The dataset has ~280k rows and 39 features, the target column being 1, 2, or 3,
representing low, medium, or high damage to the building. The goal was to predict
this damage grade from the given features.

The features include geographic data, building specifications, foundation and
land condition, and binary variables for superstructure and secondary uses.

Our final model was a RandomForest that can classify the damage grade correctly
roughly 75% of the time. We are still working to improve our model.
