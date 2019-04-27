# MNIST Comparative Study
Model	Training Accuracy	Validation Accuracy	Test Accuracy	Epochs	Learning rate	Training time (in seconds)
Neural Network	100%	97.7%	97.64%	400	0.01	577.2
Neural Network with L2 regularization
and learning-rate decay	99.62%	98.18%	98.1%	200	\frac{1}{1 + 0.001 * epoch\_num}	430.6
Convolutional Neural Network	99.75%	98.88%	99.07%	80	0.01	312.8
