# java-calculator-precourse

## 구현할 기능 목록

- [x] 사용자
    - [x] 구분자와 양수로 구성된 문자열 입력한다.
        - 쉼표(,), 콜론(:)을 구분자로 가진다.
        - 커스텀 구분자를 지정할 수 있다.
            - 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치한다.
- [x] 계산기
    - [x] 문자열을 기본 구분자, 커스텀 구분자로 분리한다.
    - [x] 분리된 문자열을 정수로 변환한다.
    - [x] 정수로 변환한 값을 더한다.
    - [x] 더한 결과를 반환한다.

## 출력

- [x] 덧셈 결과를 출력한다.

## 예외 상황

- [x] 사용자가 입력한 값이 없는 경우
- [x] 사용자가 음수와 0을 입력하는 경우
- [x] 사용자가 숫자가 아닌 값을 입력하는 경우
- [x] 사용자가 입력한 문자열에서 기본 구분자, 커스텀 구분자가 없을 때
- [x] 사용자가 입력한 값이 커스텀 구분자를 지정 못하는 경우
- [x] 사용자가 커스텀 구분자로 기본 구분자(쉼표(,), 콜론(:))와 빈 문자열을 입력하는 경우

## 테스트

### Calculator.java

- [ ]  기본 구분자로 실행에 성공했을 경우
- [ ]  커스텀 구분자로 실행에 성공했을 경우
- [ ]  기본 구분자와 커스텀 구분자가 함께 있을때 실행에 성공했을 경우

- [ ]  사용자 입력 값이 없을 때 예외가 발생한다.
- [ ]  사용자가 입력한 문자열에 기본 구분자, 커스텀 구분자가 없을 때 예외가 발생한다.
- [ ]  사용자가 커스텀 구분자를 지정 못할 경우 예외가 발생한다.
- [ ]  사용자가 커스텀 구분자로 기본 구분자(쉼표(,), 콜론(:))와 빈 문자열을 입력하는 경우 예외가 발생한다.

### Numbers.java

- [x]  사용자 입력 값이 음수일 경우 예외가 발생한다.
- [x]  사용자 입력 값이 0일 경우 예외가 발생한다.
- [x]  사용자 입력 값이 숫자가 아닐경우 예외가 발생한다.

---

## 입출력 요구 사항

### 입력

- 구분자와 양수로 구성된 문자열

### 출력

- 덧셈 결과

```
결과 : 6
```

### 실행 결과 예시

```
덧셈할 문자열을 입력해 주세요.
1,2:3
결과 : 6
```