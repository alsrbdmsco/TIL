# module

> 모듈

- 미리 만들어진 코드를 가져와 쓰는 방법
- import 모듈이름
- 사용 방법: 모듈이름.모듈안의 구성요소
```
math.pi
random.choice()
```

module example
- import math
    - 수학과 관련된 기능
- import random
    - 무작위와 관련된 기능
- import urllib.request
    - 인터넷의 내용을 가져오는 기능

> 모듈 만들기

1. 사용할 함수, 메소드 코드를 작성한 모듈 파일을 생성
2. 모듈이 쓰일 파일에 import를 사용하여 모듈을 호출
3. 사용 방법은 기존의 모듈과 동일
4. 주의할 점은 사용자가 만든 모듈과 모듈을 쓸 파일이 같은 폴더에 있어야 한다.

- 함수만들기
```
def random_rsp():
    """무작위로 가위바위보를 낸다"""
    import random
    return random.choice(['가위','바위','보'])
```
- 함수 사용하기 (import 후 함수 파일 이름 지정)
```
import test 
print(test.random_rsp())
```