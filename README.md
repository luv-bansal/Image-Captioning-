# Image-Captioning
This model generates a caption for a image. This caption describes activities of input image.

Here, this model is a combination of both CNN and RNN .
The architecture of model consists of two parts:
a) Encoder model and b)Decoder model

Encoder model consist of CNN model for encoding the input image and outputs the initial state for Decoder model.  And Decoder model takes as inputs caption and output of the Encoder model as an initial state in GRUs and outputs the image caption.

Inspiration for this project came from blind peoples. I try to help those people with technology to some extent. Those people not able to see but they can hear! 
So, I build a project in which we attach a camera at a blind person's forehead or t-shirt which gives me a frame of an image and my Image Captioning model generates a caption for each image frame and used google text to speech API for  generate voice.
