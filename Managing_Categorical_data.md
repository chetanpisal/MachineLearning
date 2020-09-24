## Managing Categorical Data

### Three Methods

#### One hot Encoding Scheme

  denote Labels with binaries (1, 0)
  


#### Dummy Coding Scheme

  Generating M -1 feature, you can eliminate first or last feature.
  

#### Effect Coding Scheme

Replace 0 with -1 if all the binary feature value is 0.
  

Categorical Encoding Examples
CATEGORICAL ENCODING
ID Name Evil
1 Luke false
2 Leia false
3 Han false
4 Vadar true

Nominal - order does not matter
_Color_: { green, purple, blue } _Evil_: { true, false } 

Ordinal - order does matter

_Size_: { L > M > S }
e.g. "Weather" is my Attribute and "Sunny", "Cloudy", "Rainy" are three categories or Labels. Therefore M = 3

One Hot Encoding Scheme (M) Binary features

One-hot Encoding also called as CATEGORICAL ENCODING

Transforms nominal categorical features and creates new binary columns for each observation.
Adding columns to your dataset of 1’s and 0’s.


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




