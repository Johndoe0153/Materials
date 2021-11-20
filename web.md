# 웹 학습

## HTML

태그는 검색해서 찾아보는 걸로

## CSS

### padding
:컨텐트 주위의 공간

### border
:padding의 바깥쪽에 놓인 실선

### margin
:요소의 바깥쪽을 둘러싼 공간

![css box](https:// media.prod.mdn.mozit.cloud/attachments/2014/11/18/9443/63d72109948ccedb5e0f0dd5f9cb3716/box-model.png)

## text-shadow
:글자에 그림자 삽입. 순서대로 `수평 오프셋px 수직 오프셋px 흐림 반경px 색상` 값을 가짐.
>`text-shadow: 2px 1px 1px #bd93f9;`

## Javascript

변수를 선언 시 let 사용  (var은 오래되어서 사용 빈도 낮음)

### 변수의 자료형들:  

####  String
:문자형
>`let String = 'Firefox';`
-> `let name = "John";` // 변수를 문자열 중간에 삽입  
-> `alert(`Hello, ${name}!`);` //  Hello, John!, 표현식을 문자열 중간에 삽입  
-> `alert(the result is ${1 + 2});` //  the result is 3

#### Number
:숫자
>`let Number = 10;`
  
####  Boolean
:참/거짓
>`let Boolean = true;`
  
#### Array
:여러 값을 하나의 단일 참조에 저장
>`let Array = ['Firefox', 10];`//  myVariable[0]과 같은 방식으로 사용

#### BigInt
:길이 상관없이 정수를 나타낼 수 있음
>`const bigInt = 1234567890123456789012345678901234567890n;`
  
#### null
:어떤 자료형에도 속하지 않으며, 존재하지 않는 값, 비어 있는 값, 알 수 없는 값을 나타낼 때 사용
>`let age = null`

#### undefined
:값이 할당되지 않은 상태
>`let age = 100;`  
->`age undefined;`   
->`alert(age);`

### typeof
:인수의 자료형을 반환하는 연산자
>`typeof String`

### const
:`let`과 비슷하나, 변수 값을 변경할 수 없을 때 사용함
>상수

### alert
:모달(확인 버튼을 누르기 전에는 모달 창를 제외한 나머지와 상호작용 불가)창 띄우기
>`alert('Hello, world!);`

### prompt
:텍스트 메시지 + 입력 필드 + 확인&취소 버튼이 있는 모달창을 띄우고, 입력 필드에 기재한 문자열을 반환. `result = prompt(title, [defualt]);`의 형식을 띔
>`prompt('Type', 'haha');`  
`title`: 사용자에게 보일 문자열, `default`: 입력 필드의 초기값(선택값)  


### confirm
:매개변수로 받은 question과 확인 및 취소 버튼이 있는 모달창을 띄우기  
>사용자가 확인을 누르면 `true`, 그 외에는 `false`를 반환

### 문자형으로 변환

>`let value = true;`  
`alert(typeof value);` // boolean

>`value = String(value);` // 변수 `value`엔 문자열 `"true"`가 저장됩니다.  
`alert(typeof value);` //  string

### 숫자형으로 변환

>`let str = "123";`  
`alert(typeof str);` // string  

>`let num = Number(str);` // `문자열 "123"`이 `숫자 123`으로 변환됩니다.  

>`alert(typeof num);` // number

### 불린형으로 변환

>`alert(Boolean(1));`  // true  
`alert(Boolean(0));` // false  

`숫자 0, 빈 문자열, null, undefinded, NaN`과 같이 직관적으로 '비어있다고' 느껴지는 값:`false`  
`문자열 0, 나머지`: `true`

>`alert(2 > 1);` // true

### 연산자

#### %
:나머지 연산자

#### **
:거듭제곱
>`2 ** 2` // 4

#### +
:문자열 결합으로도 사용 가능. 단, 피연산자 중 하나가 문자열이면 다른 하나도 문자열
>`alert('1' + 2);` //  "12"  

#### +=, *=
:복합할당 연산자
>`n+=5` // n = n + 5

#### 증가 감소 연산자

`++`: 변수 1 증가  
`--`: 변수 1 감소  

`++counter`: 전위형, 증가한 값을 바로 사용할 때  
`counter++`: 후위형, 값을 증가시키지만 기존 값을 사용하고자 할 때

###  비교

#### 문자열 비교

:첫 번째 문자열 비교해서 안 끝나면 계속함. 사전 순과 비슷하지만, 실제로는 유니코드 순서
>`alert('Z' > 'A');` // true

#### 다른 형을 가진 값 간의 비교
:비교하는 자료형이 다르면, 값을 숫자형으로 바꿈
>`alert('2' > 1)` // true

#### null & undefinded
:`null`과 `undefined`는 동등 비교(==) 시 서로 같지만 다른 값과는 같지 않다

### if문
:조건이 `true`일 떄 실행되며, 복수의 문을 실행하고자 할 경우 중괄호로 코드 블록을 감싼다.

`else`: 뒤에 이어지는 블록이 거짓일 경우 실행하고자 할 때 사용한다.  
`else if`: 여러 조건이 필요할 때 사용한다.  
