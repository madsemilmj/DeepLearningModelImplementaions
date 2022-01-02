# Image Segmentation

In this jupyter notebook, I am going to implement UNet (https://arxiv.org/abs/1505.04597), which is one of
the most popular models for image segmentation using a neural network. It was originally proposed for
biomedical domain, specically the cell segmentation. The original paper used two final output channels to
distinguish each pixel if it belongs to a specific cell or not. I am going to adopt it to COCO2017 dataset
(https://cocodataset.org/), which images of 80 different kinds of objects, for semantic segmentation task.
