# 미션 - 로또

## 기능 요구 사항
### 입력
  - 로또 구입 금액을 입력받는다. (구입금액은 1000원단위) 1000원으로 나누어 떨어지지 않을 경우 예외처리 발생
  - 당첨번호 (1~45까지의 숫자) 을 입력받는다. 번호는 ',' 로 구분 
  - 로또 구입금액을 1000원으로 나눈 몫의 값만큼 입력받는다.
  - 보너스 번호을 입력받는다
  - 입력 값은 중복을 허용하지 않는다

### 출력
  - 발행한 로또 수량, 번호을 출력한다 (오름차순으로 정렬) 
  - 당첨내역을 출력한다
    - 맞은숫자 개수 (당첨금액) - 수량 형식으로 출력
    - 5개 일치이면서 보너스볼도 일치일 경우 
      - 맞은숫자 개수, 보너스볼 일치 (당첨금액) - 수량 형식으로 출력
  - 수익률은 소수점 둘째 자리에서 반올림한다
  - 수익률 = 당첨금액 총액 / 로또 구입금액 
  - 예외 상황시 에러 문구를 출력한다. 
  - 에러문구는 "[ERROR]" 로 시작

## 🚀 구현 기능 목록
