## before syntax highlighting	
```
void f() 
{
	printf(%s,“이것은 c 코드 입니다”);
}
```

## before syntax highlighting	
```c
void f() 
{
	printf(%s,“이것은 c 코드 입니다”);
}
```

## before syntax highlighting	
```
def sumMatrix(A,B):
    answer = []

    if len(A) != len(B):
         return answer
        
    for i in range(len(A)):
        tmp = []
        for j in range(len(A[i])):
            tmp.append(A[i][j] + B[i][j])
        answer.append(tmp)

    return answer`
```

## after syntax highlighting	
```python
def sumMatrix(A,B):
    answer = []

    if len(A) != len(B):
         return answer
        
    for i in range(len(A)):
        tmp = []
        for j in range(len(A[i])):
            tmp.append(A[i][j] + B[i][j])
        answer.append(tmp)

    return answer`
```
