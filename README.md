# SMAI Assignment 2
## Name - Pranav Gupta
## Roll no. - 2021101095

All Plots and graphs(wherever asked) are attached in the Jupyter Notebooks itself.
Explanations and Observations are also provided in Markdown Cells in the Jupyter Notebook itself.


## Part 1: PCA
Part 1.1.1 and 1.1.2 are done together and PCA is applied for Dimensionality Reduction on IIIT-CFW Dataset. Based upon that Cumulative Explained Variance plot is drawn.
Part 1.1.3 involves use of pictionary dataset of previous dataset. PCA is performed on the Dataset, Value of Principal Components is varied from 1 to size of dataset. Then, the plot for accuracy is drawn for Principal Component variation. Also, other metrics such as weighted F1-Score, Accuracy, Precision and Recall are evaluated for the Dataset for different values of Principal COmponent. Also, the Analysis is done for VIT Encoder Values only and not for RESNET Encoder.
Part 1.1.4 involves use of IIIT-CFW Dataset again. Here Number of Principal Components is varied and classification is done using KNN Algorithm. Accuracies are noted for the Classifier using sklearn metrics only.
PCA Class is implemented from Scratch and the sklearn implementations are not used.

Part 1.2 involved use of new Pictionary Dataset. In this PCA is applied for 1 Principal Component, for 2 PCs, and finally for 3 PCs. Based upon that results are obtained and visualised in 2D and 3D.


## Part 2: GMM
GMM Class is implemented from Scratch with functions which were written in the Asignment PDF.
Part 2.1 involved the use of Customer Dataset. Here Gmm is fit for Cluster Number Values = 1, 3, 5, 7. Observed Results are printed and everything is implemented according to Assignment Specifications.
Part 2.2 involved the use of sklearn Wine Dataset. Here Gmm is fit for various Cluster Values from 1 to 178(size of dataset). Then, AIC and BIC Criterions were used for GMM. Optimal Cluster Values were reported for both criterions. Following that, PCA was applied and scatter plots and silhouette scores were also computed for K-means and GMM Algorithms.

## Part 3: Hierarchical Clustering
Linkage Matrix and Dendrogram were made using inbuilt functions of scipy module of python for both parts.
Linkages such as single, complete and average were used.

Part 3.1.1 involved use of new customers dataset. Hierarchical Clustering was implemented. For the Purpose of this part, each feature was analysed pairwise with all the other features. Since there are 4 features, this means 12 times Dendrogram was plotted for different pairwise featues and 3 times for each linkage metric as well.

Part 3.1.2 involved use of Gene Expression Dataset. Hierarchical Clustering was implemented, following which, clusters were drawn taking GSM613412 as the feature and varying all other Gene Expressions as other features. Based upon that, Plots were obtained. ID Attribute was dropped in the beginning since it has no physical significance in the Clustering Procedure. Linkage Variation was use of single, complete and average linkage metrics for computation of pairwise distances.

## Part 4: 

Part 4.1 involved use of KIMIA Dataset with 99 Images. In this, the Template Image was assumed to be cat1.png of the Dataset and other images were aligned w.r.t the Template Image. For this, flowchart is also explained at the end of the question and Images were saved in a Folder named 'output' in the current directory. The code assumes that output directory already exists, otherwise, it will throw error. Images were named image{i}.png where {i} varies from 0 to 98, image{0} being cat1.png.

Part 4.3 involved the use of colors dataset. In this, Inbuilt sklearn GMM was applied and then the corresponding means and covariances were printed on the console. Also, the membership of the various data points was also printed. Following this, a sample Dataset using the means and components was also generated, according to Assignment Specifications.