# READ-ME 

We have three required arguments:

--image : The path to the input image.
--prototxt : The path to the Caffe prototxt file.
--model : The path to the pretrained Caffe model.
An optional argument, --confidence , can overwrite the default threshold of 0.5 if you wish.


When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

1. The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
2. The .caffemodel file which contains the weights for the actual layers
