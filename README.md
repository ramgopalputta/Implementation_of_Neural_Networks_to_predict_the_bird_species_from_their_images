# Abstarct:
This report elucidates the process of prediction and classification of bird species from their images and 
sounds datasets with the implementation of Convolutional Neural Networks, using an R interface ‘Keras’, 
powered by TensorFlow back-end engine. A large data set with 18 species of birds that are commonly 
found in Western Washington and Seattle areas. Each species with 100 images is used in this analysis. All 
the images are colored and squared with a length and breadth of 224 pixels and 3 color channels (Red, 
Blue and Green. The entire data is split into training and testing data in the ratio 4:1 A Convolutional 
Neural Network model with various layers is built and implemented in this analysis. The model is first 
trained using the Training data and prediction is performed over the Test data. An accuracy level of nearly 
88 percent is achieved in image prediction. Accuracy levels are further raised to 95 percent by fine-tuning 
the model. 

# FEATURES OF CNN:
The CNN model is widely considered a ‘Gold Standard’ for image classification problems. When compared 
to other classification models with fully connected networks, fewer parameters are required to build the 
CNN model. Therefore, the processing time is comparatively less. This model is best suitable for image 
recognition and classification with huge number of images. 

# HOW CNN WORKS:
The CNN has many hidden layers called convolutional layers. Each of these layers contains neurons that 
are connected to neurons of the closest layer. These convolutional layers receive the input, transform the 
input in some way, and output the transformed input to the next layer. The CNN contains filters which are 
feature detectors which detect edges, corners, circles, squares etc. in an image. The deeper the network 
goes, the more sophisticated these filters become. In later deep layers, the filters will be detecting specific 
objects like eyes, feathers, beaks etc. And in even deeper layers, the filters can detect even more 
sophisticated objects like full images of dogs, cats, birds etc. There are a couple of layers which make CNN 
unique – ‘Convolutional layer’, ‘pooling layer’. Other important layers are the ‘Relu’ and ‘Fully connected 
layer’, which are common in all neural networks. The ‘Convolutional layer’ is the most important layer in 
the network. It works by placing the filter over an array of image pixels. This then creates a feature map. 
The ‘Pooling layer’ down samples or reduces the sample size of a particular feature map. This also makes 
processing much faster by reducing the number of parameters. The ‘Relu’ layer acts as an activation 
function ensuring non-linearity as the data moves through each layer in the network. Without this layer, 
the data which is being fed into each layer would lose the dimensionality that is to be maintained. The 
‘Fully connected layer’ performs classification on the data set. An additional layer is included in the model, 
which is known as ‘Dropout layer’. This layer drops out a random set of activations in a particular layer by 
setting them to zero. This helps by preventing over-fitting of data. 
