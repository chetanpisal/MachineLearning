## Managing Categorical Data

### Three Methods

#### One hot Encoding Scheme

  denote Labels with binaries (1, 0)
  


#### Dummy Coding Scheme

  Generating M -1 feature, you can eliminate first or last feature.
  

#### Effect Coding Scheme

Replace 0 with -1 if all the binary feature value is 0.
  



e.g. "Weather" is my Attribute and "Sunny", "Cloudy", "Rainy" are three categories or Labels. Therefore M = 3

One Hot Encoding Scheme (M) Binary features

Weather   S  C  R

S         1  0  0
S         1  0  0
C         0  1  0
R         0  0  1
R         0  0  1

Dummy Coding Scheme (M -1) binary features, you can eliminoate first or last feature.

Weather   C  R

S         0  0
S         0  0
C         1  0
R         0  1
R         0  1


Effect Encoding Scheme

Weather   C  R

S         -1 -1
S         -1  -1
C         1  0
R         0  1
R         0  1




