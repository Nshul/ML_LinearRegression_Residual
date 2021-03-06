# ASSIGNMENT 1

### Part 1

Click points on Canvas to visualise change in linear line

### Part 2

Residual Plot for the same

Run:

```python
python main.py
```

![Figure-1](https://github.com/Nshul/ML_LinearRegression_Residual/blob/master/images/Figure_1.png)

![Figure-2](https://github.com/Nshul/ML_LinearRegression_Residual/blob/master/images/Figure_2.png)

![Figure-3](https://github.com/Nshul/ML_LinearRegression_Residual/blob/master/images/Figure_3.png)

![Figure-4](https://github.com/Nshul/ML_LinearRegression_Residual/blob/master/images/Figure_4.png)

# ASSIGNMENT 2

Linear Regression on Data set of Anscombe's Quartet

Run:

```python
python main2.py
```

![Figure-5](https://github.com/Nshul/ML_LinearRegression_Residual/blob/master/images/Figure_5.png)

# ASSIGNEMENT 3

Linear Regression using Gradient

The Gradient keeps updating the weights as long as the error threshold is not reached.

Run:

```python
python main3.py
```

# ASSIGNMENT 4

Find-S Algorithm for [Zoo Data Set](https://archive.ics.uci.edu/ml/datasets/zoo)

Run:

```python
python main4.py
```

![Assignment-4](https://github.com/Nshul/ML_Assignments/blob/master/images/Ass4.png)

# ASSIGNMENT 5

Candidate Elimination Algorithm for Enjoy Sport(data.csv) and Another Data Set with initial -ve example

This code runs for any general data

Run:

```python
python main5.py
```

Output for Enjoy Sport
![Assignment-5](https://github.com/Nshul/ML_Assignments/blob/master/images/Ass5.png)

Output for Data with -ve first example

```python
['phi' 'phi' 'phi']
  size color shape
0    ?     ?     ?
For 1:
S:
['phi' 'phi' 'phi']
G:
    size color     shape
0  small     ?         ?
1      ?  blue         ?
2      ?     ?  triangle
For 2:
S:
['phi' 'phi' 'phi']
G:
    size color     shape
0      ?  blue         ?
1  small  blue         ?
2  small     ?    circle
3    big     ?  triangle
4      ?  blue  triangle
For 3:
S:
['small' 'red' 'circle']
G:
    size color   shape
2  small     ?  circle
For 4:
S:
['small' 'red' 'circle']
G:
    size color   shape
0  small     ?  circle
For 5:
S:
['small' '?' 'circle']
G:
    size color   shape
0  small     ?  circle
```
