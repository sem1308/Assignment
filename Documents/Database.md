# Database
* 여러 사람에 의해 공유될 목적으로 통합하여 관리되는 데이터의 집합
* DBMS
  * 데이터베이스 구성, 효율적인 데이터 조작, 관리하는 프로그램 집합체
* 메인 메모리 DBMS
  * 데이터를 메인 메모리에 저장
  * 장점
    * 기존 디스크 탐색보다 빠른 응답속도
  * 단점
    * 높은 휘발성
  * 사용회사 및 제품
    * 알티베이스 - Altibase
    * 리얼타임테크 - Kairos
    * SAP AG - SAP HANA
    * 오픈소스 - Redis
    * 오라클 - TimesTen
* SQL(RDB)
  * 관계형 데이터베이스 관리 시스템의 데이터 관리를 위한 언어
  * IBM에서 1970년대 초 도널드 D.챔벌린과 레이먼드 F.보이스가 개발
  * 장점
    * 다용도, 높은 성능
    * 데이터 일관성  
    * 정규화 -> 갱신 비용 최소화
  * 단점
    * 대량 데이터 입력 처리
    * 갱신 테이블의 인덱스 생성 및 스키마 변경
    * 어려운 컬럼 확장
    * 단순히 빠른 결과
  * 예시
    * 오라클
      * 큰 예산과 복잡한 비즈니스 요구과 기업 고객에 적합
      * 어떠한 운영체제 또는 장비에 구애받지 않음
      * 높은 이식성
      * 가동 중 백업 가능, 데이터 손실 유발 거의 없음
    * MySQL
      * 사용하기 가장 쉬움
      * 빠르고 안정적
      * 무로, 고사양 요구하지 않음
      * 웹 환경에 맞게 설계
    * MS SQL
      * 저렴한 제품 가격
      * 단순한 데이터베이스 기능
      * 대용량 처리에 좋음
      * R 데이터 분석 처리
  * NoSQL
    * 장점
      * 대용량 데이터
      * 데이터 분산 처리
      * Cloud Computing
      * 빠른 읽기/쓰기 속도
      * 유연한 데이터 모델링
    * 예시
      * 몽고 DB
        * 10gen에서 2007년 10월에 개발
        * 2009년에 오픈 소스 개발 모델로 전향
        * 동적 스키마 형 문서 허용
        * 데이터 교환 시 비산(BSON)문서 형태로 저장, 여러 서버에 분산 저장 및 확장 용이
        * 방대한 데이터 처리가 빠름
        * C++언어로 작성
        * 지원 운영 체제
          * 윈도우
          * 리눅스
          * 맥OS
      * 카산드라 DB
        * 대용량의 데이터 처리 가능
        * 노드추가를 통한 횡적으로 용량 확장
        * 여러 프로그래밍 언어 지원
          * Ruby
          * Perl
          * Python
          * Scala
          * Java
          * PHP
          * C#
        * 데이터간 복잡한 관계 정이 필요 없음
        * 뛰어난 성늘, 확장성 그리고 안정성
      * HBASE
        * 중앙에 전체 분산 시스템 통제하는 마스터를 통해 복제된 전체 데이터 일관성 관리
        * 대량 데이터를 우수한 성능으로 데이터 일관성 보장
      * Redis
        * 메모리 기반의 Key/Value Store
        * 빠른 처리속도
        * 테이터가 메모리+Disk에 저장
        * 만료일을 지정, 만료되면 자동 데이터 삭제
        * 저장소 메모리 재사용하지 않음
        * 문자열, Set, Sorted Set, Hash, List등 다양한 Data Type 
