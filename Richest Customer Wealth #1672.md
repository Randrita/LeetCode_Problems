```python
r=int(input('Enter the no. of rows:'))
c=int(input('Enter the no. of cols.:'))
```

    Enter the no. of rows:3
    Enter the no. of cols.:2
    


```python
matrix=[]
for i in range(r):
    a=[]
    for j in range(c):
        a.append(int(input()))
    matrix.append(a)
for i in range(r):
    for j in range(c):
        print(matrix[i][j], end = " ")
    print()   
```

    1
    5
    7
    3
    2
    5
    1 5 
    7 3 
    2 5 
    


```python
count=0
temp=0
for i in range(0,r):
    for j in range(0,c):
        count=matrix[i][j]+count
       
    if count>temp:
        temp=count
        count=0
    else:
        count=0
        pass
print(temp)
        
```

    10
    


```python

```
