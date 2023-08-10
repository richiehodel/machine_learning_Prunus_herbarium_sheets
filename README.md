### This repo holds jupyter notebooks and scripts associated with the manuscript:
"A phylogenomic approach, combined with morphological characters gleaned via machine learning, uncovers the hybrid origin and biogeographic diversification of the plum genus"

The notebooks here are meant to walk the reader through some of the analyses used in the manuscript. By changing directory and variable names, they could be readily modified to be used on different sets of labeled image data.

There are six notebooks. The first four are used to train, validate, and understand how a classifier that distinguishes between solitary/corymbose and tropical racemose specimen works. The next two describe how to train a classifier that distinguishes between four groups: solitary/corymbose, temperate racemose, neotropical racemose, paleotropical racemose. The classifier algorithm is then used to define the morphological space occupied by each group.
1. Trim specimens to remove top and bottom of images
2. Build a classifier distinguishing between solitary/corymbose and tropical racemose specimens
3. Calculates classification probabilities of known images to validate model robustness
4. Performs Gradient-CAM to determine pixel importance
5. Build a classifier distinguishing between four groups: solitary/corymbose, temperate racemose, neotropical racemose, paleotropical racemose
6. Uses IVIS to quantify the morphological space occupied by each group from notebook 5

* The jupyter notebooks are in this repository and available for download and can be run locally on your computer.
However, it is sometimes easier to run them in Google Colab.

* Here's a link to open notebook 1 that *trims images* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Data_Processing-trimming_cpnuc.ipynb)

* Here's a link to open notebook 2 that *builds a classifier* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Prunus_hybridization_model_cpnuc_.ipynb)
The above classifier is trained to distinguish between two categories: solitary/corybmose or tropical racemose

* Here's a link to open notebook 3 that *calculates probabilities for known images* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Prunus_testknown_cpnuc.ipynb)

* Here's a link to open notebook 4 that *performs Gradient-CAM* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Prunus_gradCAM_cpnuc.ipynb)

* Here's a link to open notebook 5 that *builds a 4-way classifier* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Prunus_4groups_temptrop.ipynb)

* Here's a link to open notebook 6 that *quantifies morphological space* in Google Colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richiehodel/machine_learning_Prunus_herbarium_sheets/blob/main/Prunus_IVIS_temptrop.ipynb)
