# format

> format

1. 문자열의 대괄호 자리에 format 뒤의 괄호안에 들어있는 값을 하나씩 넣는다

2. 문자열에 포함된 대괄호 개수 보다 format안에 들어 있는 값의 수가 많으면 정상 동작

3. 문자열에 포함된 대괄호 개수 보다 format안에 들어 있는 값의 수가 적으면 에러

```python
number = 20
welcome = '환영합니다'
base = '{} 번 손님 {}'

print(number,'번 손님',welcome)
print(base.format(number,welcome))
print('{} 번 손님 {}'.format(number,welcome))
```

- 결과 
```
20 번 손님 환영합니다.
```

이렇게 결과가 똑같이 나오는 것을 볼 수 있습니다.