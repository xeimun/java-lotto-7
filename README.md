# 구현 기능 목록 – 로또

### 입력
##### - 구입 금액 입력
##### - 당첨 번호 입력
##### - 보너스 번호 입력
##### [예외 처리] 
```
[구입 금액 관련]
  - 입력값이 숫자가 아닐 경우
  - 입력값이 빈 공백이거나 비어있을 경우
  - 구입 금액이 최대 허용 금액을 초과할 경우
  - 구입 금액이 1,000원 단위가 아닐 경우

[당첨 및 보너스 번호 관련]
  - 입력값이 숫자가 아닐 경우
  - 입력값이 빈 공백이거나 비어있을 경우
  - 입력한 번호가 허용된 범위를 벗어날 경우
  - 당첨 번호 입력 시 허용된 구분 문자를 사용하지 않을 경우
  - 당첨 번호 중 중복된 번호가 있는 경우
  - 당첨 번호의 입력 개수가 유효하지 않을 경우
  - 보너스 번호의 입력 개수가 유효하지 않을 경우
  - 보너스 번호가 당첨 번호와 중복될 경우   
```

<br>

### 로또 발행 관리
#### - 로또 구매 수량 계산
#### - 구매 수량에 따른 로또 번호 생성

<br>

### 당첨 검증
#### - 로또 번호와 보너스 번호의 일치 여부 확인
#### - 로또 번호와 당첨 번호의 일치 개수 계산
#### - 당첨 등수 판별
#### - 당첨 결과 저장

<br>

### 상금 및 수익 계산
#### - 총 상금 계산
#### - 수익률 계산 (총상금/구입 금액 * 100)

<br>

### 출력
##### - 안내 메시지 출력 (구입 금액, 당첨 번호, 보너스 번호 입력 안내)
##### - 구매 개수 및 로또 번호 출력
##### - 등수별 당첨 개수 출력
##### - 수익률 출력
