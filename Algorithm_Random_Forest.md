## Random Forest

### Type - 

{UNSUPERVISED}

### Example Inference  

	Binary **Yes** or **No**
	
	Classification

### Use cases

	Customer Analysis
	Medical Condition 


 **Inferences are generated usingn multiple Decision Trees and winner in inferences are declared**


### Random Cut Forest ANOMALY DETECTION {UNSUPERVISED}Detect anomalous data points within a set, like spikes in timeseries data, breaks in periodicity or unclassifiable points.Useful way to find outliers when it’s not feasible to plotgraphically. RCF is designed to work with n-dimentional input.Find occurrences in the data that are significantly beyond“normal” (usually more than 3 standard deviations) that couldmess up your model training.


ANOMALY DETECTIONGives an Anomaly Score to Data Points Low scores indicate that a data point isconsidered “normal” while high scores indicate the presence of an anomaly.

Scales WellRCF scales very well with respect to number of features, data set size andnumber of instances.