# ReviewWQuestion-Calculator
질문부터 시작하는 코드리뷰 1기의 계산기 앱 구현 저장소입니다.

## 구현한 기능
1. 타원형 0 이 들어간 UI
2. 사칙연산기능
3. 입력하는 자리수가 커지면 동적으로 글자가 작아지는 기능 
4. 세 자리 단위로 `,` 가 나오는 기능 
5. 두 번째 피연산자를 입력하지 않고 `=`을 입력하는 경우 이전 연산을 반복하는 기능
6. 결과가 소수점으로 나오는 경우 소수점 3자리에 반올림하는 기능 

## 해결해야 하는 기능 
1. ~`.` 을 찍으면 세 자리 단위로 찍혔던 `,`가 일시적으로 사라지는 현상~ (해결)
2. 연산을 시작하고 두 번째 탭부터 AC가 C로 변하는 현상 (첫 번째 탭 부터 바뀌어야 함)
3. 나누는 피연산자가 0인 경우 "오류"가 뜨는 대신 빈 창이 뜨는 현상 
4. 연산 결과가 아닌, 입력할 때 소수점 3자리에서 반올림되는 현상 (더 이상 입력받지 못함)
5. 연산 우선순위가 높은 것은 먼저 연산하는 기능
