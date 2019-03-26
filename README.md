# Vertebrates-Invertebrates-Classifier
Vertebrates-Invertebrates classifier with Pytorch/Fastai using OpenCV for visualization.
The dataset has been taken directly doing scraping from google search. I have used a few tools and widgets to clean it. 

The choosen network structure has been Resnet34 to reduce the training time. I have fine-tunned it unfreezing the layers and training it with smaller learning rates 
for lower layers.

In order to visualize the predictions, I have worked on two options:
1) Take a video and make live prediction visualizing the frames on the jupyter notebook with the labels and probabilities on it.
2) Take a video and write a new one with the labels and probabilities on it.
