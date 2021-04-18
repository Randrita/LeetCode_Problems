```python
R=int(input('Enter the number of row: '))
C=int(input('Enter the number of cols. : '))
```

    Enter the number of row: 2
    Enter the number of cols. : 3
    


```python
matrix=[]
for i in range(R):
    a=[]
    for j in range(C):
        a.append(int(input()))
    matrix.append(a)
```

    1
    2
    3
    4
    5
    6
    


```python
x=((list(zip(*matrix))))
print(x)
```

    [(1, 4), (2, 5), (3, 6)]
    


```python
for i in range (len(x)):
    print(list(x[i]),end='\n')
```

    [1, 4]
    [2, 5]
    [3, 6]
    


```python

```
