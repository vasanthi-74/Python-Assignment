```python
#While Loop Inside While Loop
i = 1
while i <= 3:
    j = 1
    while j <= 2:
        print("i:", i, "j:", j)
        j += 1
    i += 1
```

    i: 1 j: 1
    i: 1 j: 2
    i: 2 j: 1
    i: 2 j: 2
    i: 3 j: 1
    i: 3 j: 2
    


```python
#While Loop Inside For Loop    
for i in range(1, 4):
    j = 1
    while j <= 2:
        print("i:", i, "j:", j)
        j += 1
```

    i: 1 j: 1
    i: 1 j: 2
    i: 2 j: 1
    i: 2 j: 2
    i: 3 j: 1
    i: 3 j: 2
    


```python
#For Loop Inside While Loop
i = 1
while i <= 3:
    for j in range(1, 3):
        print("i:", i, "j:", j)
    i += 1
```

    i: 1 j: 1
    i: 1 j: 2
    i: 2 j: 1
    i: 2 j: 2
    i: 3 j: 1
    i: 3 j: 2
    


```python
#For Loop Inside For Loop
for i in range(1, 4):
    for j in range(1, 3):
        print("i:", i, "j:", j)
```
