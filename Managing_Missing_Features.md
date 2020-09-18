To increase accuracy of Model,
## Let us see how to Handle Missing Values form dataset?
### Three Ways

#### Remove the Record
when you have very large records in the data, if you have small dataset this strategy will make your dataset weak


#### Create sub-model
create sub-model to predict the missing value.
computationally expensive and time consuming
Training data to be created with the attributes other than Target Attribute.
predict the Target Attribute (M), it will be model of Training Data above


#### Automatic Strategy (mean, median mode)
This is the simplest strategy, replace missing value with Mean/Median/Mode


