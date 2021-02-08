# Bag of Visual Words
Bag of Visual words is commonly used in Image Classification. It is used to represent image in the form of features. Features consist of 2 parts: Keypoints and Descriptors. 

Keypoints refer to the most important features of an image and even if the image is rotated or altered, the keypoints stay the same. 

Descriptors are those that define the Keypoints. 

Both descriptors and keypoints are used to form a vocabulary from which a frequency histogram can be generated. This histogram can used to predict or find similar objects from the image. 

The extraction of keypoints and descriptors is done using feature extractors such as SIFT, SURF. Once the descriptors are extarcted, they are clustered using a clustering algorithm, and the centre of the cluster denotes the vocabulary. 

Then, for each image, the feature histogram is generated from the vocabularies and feature vocabularies. 

By using bag of visual words representation of the images in the dataset, we can compute the image’s nearest neighbors using nearest neighbors algorithm or another algorithm.

![alt text](https://github.com/niranjana98/Bag-of-Visual-Words/blob/main/BoVW.png)

## Reference
1. https://towardsdatascience.com/bag-of-visual-words-in-a-nutshell-9ceea97ce0fb
2. http://people.csail.mit.edu/torralba/shortCourseRLOC/

