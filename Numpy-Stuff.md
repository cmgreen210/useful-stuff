#Numpy
##Matrix Multiplication
It doesn't matter if you vector has shape (n, 1) or (n, ), you still get the same matrix multiplication result.

```python
	X = np.array([[1, 1], [2, 2], [3, 3]])
	y = np.array([2, 3])
	np.dot(X,y) # array([5, 10, 15])	
	y = y.reshape(2,)
	np.dot(X,y) # array([5, 10, 15])
```