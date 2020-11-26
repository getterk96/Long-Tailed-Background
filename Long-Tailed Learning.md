# Long-Tailed Learning

## Question Setting

* **Imbalanced Train Set and Balanced Test Set**

## Trends of Solutions
* **Data level techniques: SAMPLING**
	* **over-sampling**
		* disadvantages: overfitting to less samples
		* less followers
	* **down-sampling**
		* disadvantages: loss of information
		* less followers
	* **class-balanced sampling**
	  * combine over-sampling and down-sampling
	* **mixing minor samples**
	  * SMOTE: Synthetic Minority Over-sampling Technique
* **Loss level techniques: REWEIGHTING**
	* **loss level**: make minor classes' misclassification cost higher
		* ratio of total population to class population
	* **score level**: balance the predicting scores directly
		* Training Cost-Sensitive Neural Networks with Methods Addressing the Class Imbalance Problem
* **Others**
  * **Transfer based techniques**
  * **Clustering based techniques**

## Take-On Message

* For sampling: The size of the final population has no bearing on the results. The performance depends on the class DISCRIMINATORY INFORMATION contained in the PRUNED PORPULATION.
* SCORE LEVEL BALANCING is underdeveloped

### Training Cost-Sensitive Neural Networks with Methods Addressing the Class Imbalance Problem
* ![](moving_threshold.jpg)
* Cost based moving threshold can achieve similar performance with the sampling methods.
* Cost function should be pre-defined. 

### SMOTE: Synthetic Minority Over-sampling Technique

* ![](SMOTE.png)
* Generate synthetic examples from K-means neighbours by operating in “feature space”
* Combine over-sampling and down-sampling