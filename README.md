# neural_style_transfer
Code for neural style transfer

# Abstract
Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

# Background
The main idea behind NST: Features are extracted from low level to high level as we process the image through a CNN. That means, low level features like pixel representations are captured in low level layers(style features) and high level features such as shapes and boundaries(content features) are captured in high level layers.

# Cost functions

# Content Cost function:
Content cost function is defined by calculating the mean squared error between activation of the target image that our model is trying to converge to and the activation of the initial image that is passed through the network.

# Style cost function:
Style cost function is defined by calculating the difference between the correlations of the activations of each low level layers of both style image and target image.

