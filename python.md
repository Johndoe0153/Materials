# Python

 ## &
 :비트 and 연산자 0과 1 중 둘 다 1이여야 1
 
## **
:거듭제곱

## //
:나눗셈 결과의 소수점 이하를 버림

## []
:리스트(list)
>`"abc = ['a','b','b']` -> `abc[0]` -> ` 'a'`

## {}
:빈 사전형 
> `new_dict{'apple'} = a`

## {문자:문자}
:사전형
>`{a:b}`

## | 
: 비트 or 연산자 `0`과 `1` 중 `1`이 하나라도 있으면 `1`

## \t
:탭으로 나눌 때

## <=, >=, !=, ==
:`≤, ≥, ≠, =`

## add
:set에 원소 추가
>`set.add(x)`

## and
:둘 중 하나라도 `True`여야 `True`로 출력

## append
:리스트에서 가장 뒤에 요소를 추가

## argv
: sys에서 문자열을 받아들이기
>`sys.argv`

## avg
:평균	

## choice
:고르기	

## chr
:문자형	

## close
:open 함수의 매서드. `Write` 이후에 쓰기 종료시 사용
>`test_file.close()`

## copy
:set을 복제해서 반환(리스트에서도 사용 됨)
>`set.copy()`

# count
:리스트에서 a의 출현빈도 알려줌
>`list.count(a)`

## datetime
:날짜 및 시간 모듈
>`datetime.weekday`

### weekday
:해당일이 무슨 요일인지(0은 월요일)

### today
:오늘

### datetime
:일자 및 시간

### now
:지금

## def
: 함수 정의시 사용
>`def a():`

### 함수 바깥에서 사용 가능(안에서 바깥을 건듬)
:Gloabal scope
### 함수 안에서 사용 가능(밖에서 안을 건듬)
:Local scope"

## del
: 리스트 내 원소를 지정하여 삭제
>`del[0] ` -> 1번째 원소 삭제, `del[0:2]` -> 1번째 부터 2번째까지 지움

## elif
:두번째 if부터 개수 제한 없이 조건

## else
:조건 미성립시 처리	

## end
:end= 뒤에 붙은 걸로 마지막을 채움
>`print('hi','hello',sep='?')` -> `hi?hello"`

## exept
:try 블록에서 예외 발생시 이 블록으로 옮겨져 실행

## extend
:리스트 안에 리스트 내용을 추가
>`list a.extend(list b)`

## float
:소수형

## for
: 이하의 블록을 반복	

## goto
:터틀 모듈의 매서드. 좌표 지정해서 이동
>`t.goto(50.200)`

## if 문
:조건문

## index
:리스트에서 a의 위치를 알려줌
>`list.index(a)`

## input
:변수 어쩌고	

## insert
:리스트에서 위치를 지정해서 요소를 추가	

## int
:정수형	

## len
:길이	

## list a + list b
:요소를 합친 새로운 리스트
>`list a + list b`는 `a`와 `b`의 요소를 합침

## list f[숫자:숫자]
:좌측이 첫 요소로 우측을 마지막으로 요소추출
>`list f[0:3]`

## ln
:파일에서 두 행을 위한 개행시 사용	

## not
:반대로 표현
>`a=True` -> `not a = False`

## open
:파일 생성 및 열기
>`test_file = open('text.txt','어쩌고')`

### 어쩌고에는 'w': 쓸 준비, 쓰기모드
### 'r': 읽은 준비, 읽기모드"

## or
:둘 중 하나라도 `True`면` True`로 출력	

## pop
:해당 위치의 요소를 삭제
>`pop(1)`: 첫번째 요소 삭제

## position
:터틀 모듈의 매서드. 현위치 좌표
>`t.position()`

## randint
:조건이 True일 때까지 계속해서 반복 처리	

## random
:무작위	

## range
:`0`부터 인수인 정수보다 `1` 작은 수까지 연속된 정수	

## read
:open 함수의 매서드
>`read_str = test_file.readline()` 여러 개는 `readlines`

## remove
:요소를 지정하여 삭제	

## reserve
:현재 위치에서 역으로 요소 정렬
>`reserve()`

## return
:함수 정의하기 종료	

## runtime error
:맞춤법 오류	

## sep
:sep= 뒤에 붙은 걸로 ''로 구분한 걸 채움
>`print('hi','hello',sep='?')`-> `hi?hello"`

## set
:동일 원소를 비허용하는 리스트
>`set={'a','b'}`

## sort 
:오름차순으로 정렬
>`sort()`

## split
:`(' ')` 안의 것으로 구분
>`address = 'Seoul, Korea'` -> `address.split('o')` -> `['Se', 'ul', 'K', 'rea']"`

## str
:문자열로 변환

## strip
:문자열 전후의 불필요한 공백 또는 제어문자 제거	

## syntax error
:문법 오류	

## sys
:명렬줄 인수를 다루기	

## try
:이하 블록을 실행	

## tuple
:리스트의 일종으로 내부 원소가 고정됨 
>`tuple=('shy','sky')`

## type
:변수 타입을 알려줌

## update
:set에 여러 원소를 추가 ()로 묶어서 하나로 만들어야 함
>`set.update((x,y,z))` -> `update(((x,y,z),(a,b,c)))`

## upper
:모든 문자를 대문자로 변환	

## while
:while 이하의 조건이 참일 동안 계속 실행. 조건 확인은 while이 있는 구문에서만 함
>`while a == 0:
    print('a는 0이다')`

## writelines
:데이터 여러 개 쓰기
>`test_file.writelines(date)`

## 인스턴스
:클래스 여러 기능 쓰도록 하는 것

## 할당연산자
:`/=` 등등 `+, -, * `도 마찬가지
>`a/=2` -> `a = a/2`

## range
:리스트 기반, `()`안에는 범위가 들어감
>`range(5): 0,1,2,3,4 range(1,5):1,2,3,4 range(1,14,4): 1,5,9,13`

## break
:`range` 루프에서 `break` 이하의 것을 실행하지 않고 탈출	

## continue
:`range` 루프에서 `continue` 이하의 것을 실행하지 않고(스킵) 코드를 진행

## iterable
:리스트, 튜플, 집합, 문자열은 이터러블(데이터 여러 개 담을 수 있는 것)

## list&range
:리스트가 값을 미리 저장하면, 랭지는 값을 그때마다 계산해서 준다	

## keywords 
:모듈의 한 종류	

## math
:모듈의 한 종류
>`print(math.ceil(9.5)` `ceil`은 올림(반올림 할 때 올림)을 의미함.

##  random
:모듈의 한 종류
>`random.random()` 0부터 1사이의 `float`형 값을 랜덤으로 반환
> `randome.sample` 순서 있는 데이터를 임의의 순서로 선택해 `list` 생성

## decimal
:소수형 숫자를 깔끔하게 정리해줌
>`from decimal import*`
