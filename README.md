# java-study

## IntelliJ 단축키 정리

1. 코드 작성 및 자동 완성

- ` Ctrl + Space ` : 기본 코드 자동 완성. 변수, 메서드, 클래스 이름을 빠르게 입력할 때 유용.
- ` Ctrl + Shift + Space ` : 스마트 자동 완성.
- ` Alt + Insert ` : 생성자, Getter/Setter, toString 등 코드 생성.

2. 코드 포맷팅

- ` Ctrl + Alt + L ` : 코드 자동 정렬 및 포맷.
- ` Ctrl + Shift + Alt + T ` : 리팩토링 메뉴 (변수 이름 변경, 메서드 추출 등).
- ` Ctrl + Y ` : 현재 줄 삭제.
- ` Ctrl + D ` : 현재 줄 복사.
- ` Ctrl + / ` : 현재 줄 주석 처리.
- ` Ctrl + Shift + / ` : 블록 주석 처리.

3. 라이브 템플릿

- `psvm` + `Tab` : `public static void main(String[] args)` 자동 생성.
- `sout` + `Tab` : `System.out.println()` 자동 생성.
- `fori` + `Tab` : `for 루프` 생성.
- `iter` + `Tab` : `foreach 루프` 생성.

4. 실행 및 디버깅

- `Shift` + `F10` : 현재 실행 중인 프로그램 재실행.
- `Shift` + `F9` : 디버깅 시작.

<br></br>

--------------------------------


## 기본형과 참조형

* 기본형 (primitive type) : `실제 값`을 저장. `boolean`, `char`, `byte`, `short`, `int`, `long`, `float`, `double` 

* 참조형 (reference type) : `null` 또는 어떤 값이 저장되어 있는 `주소`를 값으로 가짐. 

<br>

`Date today = new Date();`

- 객체를 생성하는 연산자 new 의 결과는 `생성된 객체의 주소`.
- 이 주소가 참조변수 `today`에 저장.
- 이 참조변수를 통해 생성된 객체를 사용할 수 있다. 

<br></br>


---------------------------------------


## 상수와 리터럴 (constant & literal)

* 상수 : 선언하는 방법은 변수 타입 앞에 키워드 `final`을 붙임.

* 리터럴 : 그 자체로 값을 의미

```java
int year = 2024;
// year : 변수, 2024 : 리터럴
final int MAX_VALUE = 100;
// MAX_VALUE : 상수, 100 : 리터럴
```

### 리터럴의 타입과 접미사

리터럴도 타입이 있음.

- 정수형 : L (long 타입)
  
  `long big = 100_000_000_000L;  // long big = 100000000000L;`

- 실수형 : f(F), d(D)

  `float pi = 3.14f;`
  `double rate = 1.618d;`

  - `double`은 생략 가능.