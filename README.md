# Relationship Between Stances on Controversies and Position in the Epistemological Space

Final Project for [Computational Content Analysis](https://github.com/Computational-Content-Analysis-2020), Spring 2020, The University of Chicago

Nak Won Rim

* Note that I did not include any of the data (both survey and texts) to the repository. Since the all the data I used is related to copyright issues or privacy issues and this repository is public, it would be serious violation of many procedure if I upload the data.
* On similar vein, I seldom printed out the data (even if it is processed) in the Jupyter notebooks. I saved a lot of them to pickle files or csv files, so please contact me if you want to take a look at middle data-product for grading.
 
## Codes Structure

* `1_Data Accumulation and Cleaning.ipynb` contains codes to gather and clean data for analysis. Some information used for the "Descriptive Statistics" are also printed out here.
* `2_Doc2Vec Construction, author similarities, and KMeans.ipynb` contains codes to create the doc2vec model and compute results used for "Direct Comparision of the Survey Responses and the Author Vectors". Some information used for the "Descriptive Statistics" are also printed out here.
* `3_Building and Labeling Survey Dimensions.ipynb` contains codes to build the survey dimension and tries to label the dimensions ("Building and Projecting to Survey Dimensions" section and "Labeling the Survey Dimensions" section). It also contains codes for the Discussion section.
* `4_Visualizations.ipynb` contains codes for creating Fig. 1 and wordcloud used for prettifying the final presentation.