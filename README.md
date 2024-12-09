# CryptoClustering

# Author: Paul Keller
# Submission Date: December 9, 2024

# The purpose of this activity is to use Machine Learning to create a model that clusters different 
# types of crypto currency. The first example uses K-Means modeling of the scaled data set. The data set
# is scaled, meaning it is adjusted so that one feature is not more biased in analysis because of weighted 
# value. A test is then run on the data to determine what would be the optimal value of k for a K-Means
# model. In this case, the optimal value of k is 4. Finally, the K-Means model is created and fitted
# with the scaled data set. From plotted data, an unusual occurence is that two of the clusters are only
# made up of one data point. The currency known as ethlend is far off on its own. Another known as 
# celsius-degree-token is on its own but could certainly be annexed into the cluster that include 
# digibyte based on its relative proximity. The second example uses a Principal Component Analysis (PCA)
# to reduce the number of features and then run another K-Means model. Using three components, the scaled
# data set is then fitted for a PCA and using these three components, approximately 99.98% of the total
# variance is explained. Another test is then run on the data to determine the optimal value of for a 
# K-Means model. In this case, the optimal value of k is 2. Finally, the K-Means model is created and
# fitted with the scaled PCA data set. From plotted data, one of the two clusters contains only one data
# point. This data point is ethlend, which was also in its own cluster in the first model. It can be
# gleaned from these two models that ethlend may be the most unlike the other crypto currencies in the 
# data set.