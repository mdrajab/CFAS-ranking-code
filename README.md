# CFAS-ranking-code
CFAS Neuropathological Assessment of Dementia Using Machine Learning Feature Selection (Python Code Scripts)

Two folders are included: -
1.Data: two main files are need to run the scripts (CFAS_NeuropathologyData May 2018.xlsx) and (CFAS_ClinicalData.csv) and the rest of files are already in   		the folder which are needed for the scripts.
2.Python: consists of 5 scripts

The python notebook scripts consist of 5 scripts, where each script does certain tasks: -
Note: Scripts must run from the 1st to the 5th script.
1.CFAS Distribution and Correlation Figures.ipynb: prepare the data for showing distribution and feature correlation.
2.CFAS Ranking Neuropathology Features.ipynb: ranks neuropathology features based on sum of weights from filter methods computed by WEKA.
3.CFAS Classification of the Ranked Neuropathology Features.ipynb: prepares ranked features and samples for classification using 7 algorithms and show the performances using different measures.
4.CFAS Misclassified Cases for Neuropathology Features.ipynb: prediction models to show the misclassified cases using the 7 algorithms and show the cluster 	heatmap. Also, prepares clinical data with the 3 clusters and pass the file to be used for clinical signature created by Emmanuel A. Jammeh GitHub 		(https://github.com/emmanueljammeh/cfas). The program returns a file shows the features with their coefficient values that are associated with the three 	clusters (FP, FN, and TP&TN). Lastly, it shows the clinical signature figure.
5.CFAS Misclassified Cases for Top 8 Neuropathology + Selected Clinical Features.ipynb: prediction models to show the misclassified cases using the 7 		algorithms with the top 8 neuropathology and 10 clinical features and show the cluster heatmap. Lastly, shows the held-out 32 cases for top 8 neuropathology and 10 clinical features.

![image](https://user-images.githubusercontent.com/8477744/150014007-5487dea4-8174-4d51-80b4-b8ed5299cea9.png)
