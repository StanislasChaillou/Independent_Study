## Week 2

**Goals:** Implement Convolutional Neural network to classify pictures of 3D objects, based on pretrained models.

**Results:**
- VGG model (1):
	- Easy to train
	- Accuracy around 0.58 on validation set
	- Limited for image recognition
- Convolutional Neural network:
	- Long training. Too for personal laptop, without GPU
	- Accuracy potentially higher than standard neural net model
	- Accuracy around 0.69 on validation set after 3 hours of training

**Next step:** Leverage pretrained models to speed up training time, and increase accuracy on validation set.

---------------------------------------------------------------------------------------------------------------

Computational Graph:

**(1)VGG**

_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
input_2 (InputLayer)         (None, 100, 100, 3)       0         
_________________________________________________________________
block1_conv1 (Conv2D)        (None, 100, 100, 64)      1792      
_________________________________________________________________
block1_conv2 (Conv2D)        (None, 100, 100, 64)      36928     
_________________________________________________________________
block1_pool (MaxPooling2D)   (None, 50, 50, 64)        0         
_________________________________________________________________
block2_conv1 (Conv2D)        (None, 50, 50, 128)       73856     
_________________________________________________________________
block2_conv2 (Conv2D)        (None, 50, 50, 128)       147584    
_________________________________________________________________
block2_pool (MaxPooling2D)   (None, 25, 25, 128)       0         
_________________________________________________________________
block3_conv1 (Conv2D)        (None, 25, 25, 256)       295168    
_________________________________________________________________
block3_conv2 (Conv2D)        (None, 25, 25, 256)       590080    
_________________________________________________________________
block3_conv3 (Conv2D)        (None, 25, 25, 256)       590080    
_________________________________________________________________
block3_pool (MaxPooling2D)   (None, 12, 12, 256)       0         
_________________________________________________________________
block4_conv1 (Conv2D)        (None, 12, 12, 512)       1180160   
_________________________________________________________________
block4_conv2 (Conv2D)        (None, 12, 12, 512)       2359808   
_________________________________________________________________
block4_conv3 (Conv2D)        (None, 12, 12, 512)       2359808   
_________________________________________________________________
block4_pool (MaxPooling2D)   (None, 6, 6, 512)         0         
_________________________________________________________________
block5_conv1 (Conv2D)        (None, 6, 6, 512)         2359808   
_________________________________________________________________
block5_conv2 (Conv2D)        (None, 6, 6, 512)         2359808   
_________________________________________________________________
block5_conv3 (Conv2D)        (None, 6, 6, 512)         2359808   
_________________________________________________________________
block5_pool (MaxPooling2D)   (None, 3, 3, 512)         0         
=================================================================
Total params: 14,714,688
Trainable params: 14,714,688
Non-trainable params: 0
________________________
