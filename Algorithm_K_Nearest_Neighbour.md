## K-Nearest Neighbour

### Type - 

**Supervised**

### Example Inference  


	Classification


### Use cases

	Recommendation Engine
	Similar Artricles and objects

### How to determine the value to use for K

Make K large enough to reduce the influence of outliers.
Make K small enough that classes with a small sample size lose incluence.



### K-Nearest NeighborAn index-based, non-parametric method for classification orregression. For classification, the algorithm queries the kpoints that are closest to the sample point and returns themost frequently used label as the predicted label. Forregression, the algorithm queries the k closest points to thesample point and returns the average of the feature values aspredicted value.Predicts the value or classification based on that which you areclosest. It can be used to classify or to predict a value (averagevalue of nearest neighbors).{SUPERVISED}