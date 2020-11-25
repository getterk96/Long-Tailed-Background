# Long-Tailed Learning
## Take-On Message
* METRIC CLASSIFIERS based on distance learning better than normal classifier.
* TRANSFORMATIONS OF INPUT SPACE can further improve the performance, ONLY FOR METRIC CLASSFIERS.
* For sampling: The performance depends on the class DISCRIMINATORY INFORMATION contained in the PRUNED PORPULATION.

## Trends of Solutions
* Data level techniques: SAMPLING
	* upsampling
		* disadvantages: overfitting
	* downsampling
		* disadvatanges: loss of information
* Algorithm level
* Cost sensitive learning
	* loss level: make minor classes' misclassification cost higher
		* ratio of total population to class population
	* score level: balance the predicting scores directly
		* Training Cost-Sensitive Neural Networks with Methods Addressing the Class Imbalance Problem

### Training Cost-Sensitive Neural Networks with Methods Addressing the Class Imbalance Problem
* ![](moving_threshold.jpg)
* Cost based moving threshold can achieve similar performace with the sampling methods.
* Cost function should be pre-defined. 