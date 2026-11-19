# ds340w_parentpaper1_mbao
Shared R notebook between group members for our project.

NOTES:
1.  All main functions of the project except for preliminary data pre-processing, can be found in "doc.Rmd." Run the entire notebook to achieve the results reported in our paper.
2.  "data_preprocessing.Rmd" explains the preliminary data pre-processing that took place. This process involved a manual screening process to select features that were theorized to be significant towards predicting lung cancer, and using the "MatchIt" nonparametric matching algorithm to create a 1:3 ratio of observations with and without lung cancer. This document DOES NOT need to be run in order to achieve the same results found in our paper.
3.  If you wish to run "data_preprocessing.Rmd," extract the data found in the Data folder. If you extract the .XPT file to the folder it is already in ("Data\LLCP2023XPT"), it should be in place to run the code. If this doesn't work, rename the dataset to "LLCP2023.xpt." If this still does not work, please contact the authors of these documents.
