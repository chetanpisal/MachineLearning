## Label and one hot enncoding

Machine learning algorithms use numbers
User **Label encoding** to replace string values

Machine learnning looks for patterns and relationship
User **one hot encoding** for categorical features

1.	One Hot Encoding Scheme

# of Binary Features will be equal to the # of Categories (M = 3)

for examle Weather : Sunny, Cloudy Rainy

**Label**	**Binary Features**

Weather		Sunny(S)	Cloudy(C)	Rainy(R)

S		 1		0		0

S		 1		0		0

R		 0		0		1

C		 0		1		0

C		 0		1		0


3.	Effect Coding Scheme

M - 1 Features, either Remove _Sunny_ or _Cloudy_

**Label**	**Binary Features**

Weather		Cloudy(C)	Rainy(R)

S		 -1		-1

S		 -1		-1

R		 0		1

C		 1		0

C		 1		0

