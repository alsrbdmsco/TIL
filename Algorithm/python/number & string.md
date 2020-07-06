# 숫자와 문자열

> 숫자열

```python
num = 10 #숫자
print (num)
```
- 결과 : 10

```python
num = '10' #숫자
print (num)
```
- 결과 : 10

위에 결과는 같지만 다른점이 있다. 아래를 보자 !

```python
num = 10 #숫자
num = num + 1
print (num)
```
- 결과 : 11

```python
num = '10' #숫자
num = num + 1
print (num)
```
- 결과 : 에러

이와같이 문자열로 쓰면 에러가 나는데 그 이유는 python이 문자보다 숫자를 더 잘 활용하기 때문이다.

-----------

> 숫자의 계산 

```python
num = 1 + 1
multiply = 5 * 5
divide = 20 / 4
power = 2 ** 10
remainder = 15 % 2
print(num,multiply,divide,power,remainder)
```
- 결과 : 2 25 5.0 1024 1

이 처럼 사칙연상을 할 수도 있다.

-----------------
> 문자열
```python
text = '20' + '10'
num = 20 + 10
print(text, num)
```
- 결과 : 2010 30
------------
> 정리

문자열은 화면에 그대로 출력이 가능하고 따옴표로 둘러싸서 표시가 가능하다. 

숫자는 수학 연산이 가능하다.
