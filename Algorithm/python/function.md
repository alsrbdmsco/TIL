# function

> 함수

반복되는 일을 할 때 편하게 사용할 수 있다.   
함수를 호출을 해야 출력이 가능하다.
- def는 define,이고 '정의' 라는 뜻이다.

```python
def function()
    print('안녕하세요')
```
- 결과 : 아무것도 나오지 않는다.

```python
def function()
    print('안녕하세요')

function()
```

- 결과 : 안녕하세요
---------------------

> 매개변수
- 함수를 정의할 때 사용하는 이름
> 실행인자
- 함수를 실행할 때 넘기는 변수,값
> 매개변수와 실행 인자
```
1. 매개변수와 실행 인자의 개수는 동일해야 한다.
2. 여러 개일 경우 쉼표로 구분

def print_round(number):    # 함수의 정의
    rounded = round(number)
    print(rounded)  

print_round(4.6)        # 함수의 호출
print_round(2.2)
```
- 결과 : 5 2
--------------------
> 함수의 값
- reutrn을 이용하여 값을 돌려줄 수 있다.

```python
 def add_10(value):
        result = value + 10
        return result

    n = add_10(5)
    print(n)
```
- 결과 : 15

여러 값을 반환 할 때에는 return 뒤에 여러 값을 쉼표로 구분해서 보내고, 받을때도 구분해서 받는다.

-------------------