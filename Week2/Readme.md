## Week 2

**Goals:** Implement Convolutional Neural network to classify pictures of 3D objects, based on pretrained models.

**Results:**
- **VGG model**:
	- Short training time
	- Accuracy around 0.8 on validation set
	- Strong overfitting after 20 epochs

![alt text](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week2/IMG/acc.png)
![alt text](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week2/IMG/loss.png)

- **ResNet50**:
	- Long training time
	- Accuracy around 0.65 on validation set. Noisy Accuracy.
	- Very Strong Overfitting after 60 epochs. 
	
![alt text](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week2/IMG/acc_1.png)
![alt text](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week2/IMG/loss_1.png)

**Next step:** Add hidden layers (maxPooling and DropOut) to counter overfitting. Try other pretrained model and compare performance.
