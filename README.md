# Kamlin-Pillay_217047298_comp700
Comp700 Major Honours Research Project
Instructions to Run Models (on the three datasets, but Cresci-2015 for testing):

Model ii:
Preprocess.py performs feature extraction and conversion of the dataset into the required format. 
LRclassification.py performs training of model and bot classification.
The dataset name in line 152 of LRclassification.py can be changed for use on the different datasets, currently set to “cresci-2015”

Model iii:  
Preprocess.py performs conversion of the dataset into the required format.
Dataset is set to “cresci-2015”
The three train.py files work for the corresponding datasets.

Model iv: 
Dataload2.py and The gcn2.py model is used for cresci-2015, the py files for the other datasets are labelled by their name

Model v:
The dataset can be worked on by opening the corresponding folder
For each folder, preprocess.py must be run first followed by train.py for the BotRGCN model.

Model vi and vii:
Model vi and vii follow the similar steps as model v


I was able to reproduce model ii on google colab. the notebook has been uploaded to moodel. 
with other models i experienced runtime crashes and running out of memory so i had to run those models offline, locally, 
on a high spec pc



