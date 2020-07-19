# for in range

> range

- 필요한 만큼의 숫자를 만들어내는 유용한 기능

```
for i in range(5):
    print(i)

- 결과
0
1
2
3
4
```

> enumerate

- 리스트가 있는 경우 순서와 리스트의 값을 전달하는 기능

```
names = ['철수', '영희', '영수']
for i, name in enumerate(names):
    print('{}번: {}'.format(i + 1, name))

- 결과
1번: 철수
2번: 영희
3번: 영수
```