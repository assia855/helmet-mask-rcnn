# helmet-mask-rcnn
# Dataset prepartion
In this project I used a small helmet images dataset that i collect from internet, which contains a 63 different helmet images. I divide them to 52 train images and 11 validation images. I annotate them using https://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html platform after applying polygon on each image I save the annotation in via_regio_data.jason for validation images and training images. 
# training the model
For the training I used the google colab gpu by following this tutorial that I recommend: https://github.com/RomRoc/maskrcnn_train_tensorflow_colab/blob/master/maskrcnn_custom_tf_colab.ipynb, also https://github.com/matterport/Mask_RCNN. 
# The prediction
