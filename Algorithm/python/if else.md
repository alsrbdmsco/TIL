# If-else

> else
1. if의 조건이 맞지 않는 경우 항상 실행
2. 반드시 if뒤에 나와야 한다.

```python
if True:
    pass # 조건이 참일 때 실행
else:
    pass # 조건이 거짓일 떄 실행
```

> elif

1. else 와 if의 결합으로 조건이 맞지 않는 경우 다른 경우를 검사
2. 기능의 차이가 아닌 보이는 것의 차이


```python
num = 10

if num == 0:
    result = num   # 조건이 참일 때 실행
elif num == 10:
    result = num  # 다른 조건이 참일 때 실행
else:
     result = '나머지'    # 조건이 거짓일 때 실행

print(result)
```
- 결과 : 10
---------------