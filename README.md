# PerovskiteQD
ML Predictions of optical properties of halide perovskite Quantum Dots

File "PerovskiteDatabase.xlsx" is a database manually collated from experimental papers for optical and structural properties of halide perovskite materials.
Features of this database include "Material, composition, synthesis method, crystal structure, type of perovskite (Single/ double/ other), Dimensionality (morphological), crystal features, ionic radii and tolerance factors (goldschmidt's and bartel's), optical measurements, and reference".

File "Single.ipynb" is a combination of nested for loops for generating compositional and ionic features for hypothetical single perovskite quantum dots, used later for band gap predictions. File "single.xlsx" is the resulting excel file from this code for predictions later.

Similarly Files "A2BBX6_1_3.ipynb" and "A2BBX6_2_2.ipynb" are feature generation code notebooks for double perovskites with +1,+3 and +2,+2 oxidation states of B,B' cation sets respectively. Files "A2BBX6_1_3.xlsx" and "A2BBX6_2_2.xlsx" are resulting excel files from this code for predictions later.

File "EgPredict.ipynb" is python based jupyter notebook for training regression models and using best model for prediction of hypothetical compositions. Files "single_eg.xlsx" and "double_eg.xlsx" are the resulting predictions.

#Any data used from this repository should be cited as : 
