Schedule Manager (Java + MySQL)

**개요**
Java Swing과 MySQL을 활용한 GUI 기반 일정 관리 프로그램
데이터베이스에 저장된 항목(Subject, Time, Whattodo 등)을 드롭다운으로 불러와서
사용자가 조합한 일정을 실시간으로 화면에 출력하고, 간편하게 스케줄을 관리



**주요 기능**

MySQL 연동 
  `timeschedulers` 데이터베이스에서 일정 구성 요소 불러오기

드롭다운 스케줄 구성
  - Subject  
  - Time  
  - Whattodo  
  - Monthly / Weekly / Daily

실시간 일정 저장 및 표시 
  - "Save" 버튼 클릭 시 화면 하단에 스케줄 내용이 누적 출력
  - 스케줄 항목은 프로그램 실행 중 `List<String>`에 저장

GUI 구성
- Java Swing 기반 사용자 인터페이스
- `JComboBox`로 항목 선택
- `JScrollPane`을 통해 스케줄 목록 스크롤 표시

기술 스택
- Java 
- Swing
- MySQL 
- JDBC

**데이터베이스 설정**
DB 이름: `timeschedulers`
