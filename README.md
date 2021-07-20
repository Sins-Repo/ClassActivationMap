# Class Activation Map
Have you ever wondered what a Convolutional Neural Network (CNN) considered while making predictions? <br/>
You can visualize it with class activation map. A heatmap of *'Class Activation'* is generated over the input image to look for specific features, features that may eventually influence the final prediction of the model.

<br/>
<br/>

# Setting
* Model used: MobileNetV2
* Platform: Colab
* Language: Python

<br/>
<br/>

# Warm-up
Let's take an image of goldfish and see how it works <br/>
Prediction: Goldfish <br/>
<br/>
<img src="img/goldfish.png" width="500">

<br/>
<br/>

# How about outdoor scene image? 
Both RGB (3 channels) & grayscale (1 channel) work fine <br/>
Prediction: Alp <br/>
<br/>
<img src="img/outdoor.png" width="900">

<br/>
<br/>

# How about indoor scene image?
Surprise ✨ <br/>
Prediction: Home Theatre <br/>
<br/>
<img src="img/indoor.png" width="500">

<br/>
<br/>

# Key Takeaway
* If you plan to use your own pre-trained model / pre-trained weights, says 300+ classes, with this example. It doesn't work
* (samples, 1000) is expected in this example, which I've placed a short comment in the code. 1000 refers to the number of classes (ImageNet) 
* For more information, kinly refer to the documentation for `decode_predictions`

<br/>
<br/>

# Reference
* Learning Deep Features for Discriminative Localization
