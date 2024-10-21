# java-calculator-precourse

## [기능 구현]

### 1. 쉼표(,)와 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환
- View를 만들어 주면서 MVC 환경 세팅하기
- 쉼표와 콜론을 구분자로 입력 받도록 구현. But, 이후 커스텀 구분자를 고려해서 확장성 있게 구현하기

### 2. 애플리케이션 실행 환경 구축 및 테스트
- 쉼표와 콜론을 구분자로 입력 받고 값을 출력할 수 있도록 구현하기
- 의도한대로 실행이 되는지 테스트 코드 실행

### 3. "//"와 "\n" 커스텀 구분자 사용 로직 추가
- 유효성 검사 클래스 로직 수정
- 계산 처리를 도와주는 Utils 클래스 및 메서드 생성하기

### 4. 오탈자 및 기능 점검
- 기능 구현에 대해 잘못된 로직이 있는지 확인하기
- 입출력 점검하기

### 5. 중복 코드 제거 및 구분자 관리 로직 수정
- 구분자를 관리하는 전역 변수를 String 타입으로 두고 사용했었는데 맘에 들지 않았음
  - 구분자를 담는 List 활용으로 수정
- Utils 클래스와 유효성 검사 클래스의 로직이 비슷한 부분이 많아서 일부 수정함
