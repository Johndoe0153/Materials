# Go

## 프로그램을 읽는 법

```go
package main

import "fmt"

// 주석입니다

func main() {
    fmt.Println("Hello, World")
}
```

### 패키지 선언

```go
package main
```

모든 Go 프로그램은 반드시 패키지 선언으로 시작

### 패키지 불러오기

```go
import "fmt"
```

### 주석

```go
//
```

### 함수 선언

```go
func main() {
    fmt.Println("Hello World")
}
```

```go
func 함수명 {

}
```

의 형식으로 이루어짐

```go
fmt.Println("Hello World")
```

`fmt` 패키지 내의 `Println` 이란 함수에 접근  
`Hello World` 가 담긴 새 문자열을 생성해서 해당 문자열을 첫번째이자 유일한 인자로 함수를 호출

## 변수와 상수

>변수는 변할 수 있는 값이지만, 상수는 변할 수 없는 값

### 변수

`var` 를 키워드를 사용하여

```go
var a int // a는 변수명 int는 변수타입
```

로 선언하기도 하지만, 아래와 같이

```go
var f float32 = 11
```

변수 선언문에서 변수 초기 값을 할당하기도 함

또한 선언된 변수가 사용되지 않으면 에러 발생함. 동일한 타입의 변수가 여러 개 있다면 변수들을 나열하고 마지막에 타입을 한 번만 지정

### 상수

`const`를 키워드로 사용하여

```go
const c int = 10 // c는 상수명 int는 상수타입 10은 상수값
```

의 형식처럼 선언하나, 상수타입을 생략하더라도 자동으로 추론하는 기능이 사용되기에

```go
const c = 10
```

처럼 사용 가능하기도 함. 또한 여러 개의 상수들을 묶어 지정할 때는

```go
const (
    Visa = "Visa"
    Master = "MasterCard"
    Amex = "American Express"
)
```

## 데이터 타입

### 정수

여러 가지가 있으나 일반적으로 `int` 타입을 사용

### 부동 소수점 수

이 역시 여러 가지가 있으나 일반적으로 `float64`를 사용

### 문자열

`string`을 사용

Back Quote(``)로 둘러 싸인 문자열은 Raw String Literal이라 부르며, 별도로 해석되지 않고 Raw String 그대로 나타남. 또한 여러 줄의 문자열을 표현할 때 자주 사용
>`\n`의 경우 줄바꿈이 아니라 그 자체로 해석

쌍따옴표(" ")로 둘러 싸인 문자열은 Interpreted String Literal 이라 불림. 여러 줄에 걸쳐 쓸 수 없고, `\n`을 줄바꿈, `\t`를 탭으로 사용하는 이스케이프 문자열을 사용 가능. 여러 줄로 사용하기 위해서는 `+` 연산자로 결합하여 사용

### 불린

`&&`: and  
`||`: or
`!`: not