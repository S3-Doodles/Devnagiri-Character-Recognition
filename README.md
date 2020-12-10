# Devnagiri-Character-Recognition
Handwritten devanagari character (UCI Dataset) recognition has been performed using Neural Networks. 

Features of the characters are extracted using Convlution Neural Network and Deep Neural Networks. 

The extracted features are then used to predict the characters using Classifiers: Random Forest, KNN and Multi-layer perceptron. 

Efficiencies of each are studied under different scenarios.

Feature Extraction: Convolution Neural networks (CNN) has been the best feature extraction Neural network used so far by various authors. Here, the scope has been tested and experimented by using Dense Neural networks in combination to CNN. “RELU” activation function is used for input and hidden layers and “sigmoid” activation function is used in the output layer.The features extracted from the dense layers are then passed to the classification model.

Following classifiers which are popular for multiclass classification are used to classify the target labels from the extracted features:

Random Forest Classifier:
● A random forest fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy.

● For model trained on all 36 characters the accuracy of Random Forest Classifier was found to be in a range of 68% to 78%

● For a model trained and validated on limited number of characters the accuracy was around 85% to 90%

Multi-Layer Perceptron Classifier:
● One of the popular classifiers for multiclass classification which uses stochastic gradient descent to optimize log-loss function.

● For fully trained and validated network across 36-character images the accuracy of MLP was around 74% to 80 %

● For model validated on limited number of character images the accuracy of this classifier was between 87% to 92%

K-Nearest Neighbor Classifier:
● K Nearest Neighbor classifier implements the k-nearest neighbors vote.

● For all 36 characters trained and validated model, KNN had a classification accuracy of around 78% to 82%

● KNN had an accuracy ranging between 88% to 92% for model trained and validated on small number of target classes.

CONCLUSION: Handwritten character recognition is still a research area of burning pattern recognition. Character recognition of handwritten Devanagari script is a difficult task considering the similarities between its characters. With the use of Neural Networks for extracting the important features of the character in the images has been very useful in mining the characteristics of the image and hence making classification of the characters simple using various multiclass classifiers. Moreover, experimenting with full and partial images of the characters using different neural network architecture has helped understand how the quality of the extracted features change, thus affecting the classification models and its accuracy. To conclude, Handwritten character recognition, Image processing, Feature extraction, neural networks are the various popular fields of research and the insights of these topics can be obtained from the report.


<b> contributors </b>

<b> 111903040 : KETAKI JADHAV

111903042 : KRUTI WALKO

111903045 : LAWANYA CHAUDHARI

111903049 : NEHA TORKAD </b>
  
