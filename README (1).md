
# Face Classification Using Unsupervised Leanring

Face Classification using an unsupervised approach in which similar images are clustered
together and any image which is given as an input and it will be assigned a cluster to which it is
most similar to.

## Table of Content

 - General Info
 - Technologies Used
 - Added
##  General Info
First we clean our data and separate mask and non mask images after that we reduce the
image size during the reading of files, since the dataset is large so direct clustering is not
possible. Autoencoder is used to resolve this issue and so that compressed image can be
used in processing and the low dimensionality images are clustered using K-means clustering
and this allows us to classify different faces by the clustering of the faces.
## Technolgies

-Python, Pandas, Numpy, CV2, Matplotlib.pyplot, Tensorflow, Keras
## Database
Link for the file with face images: https://drive.google.com/file/d/1wSW18_sQzlQ7xN3Y41UhfOlm
