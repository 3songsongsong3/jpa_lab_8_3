# 네이티브 SQL jpa_lab_8_3

## 네이티브 SQL에 대하여 
JPQL은 표준 SQL이 지원하는 대부분의 문법과 SQL 함수들을 지원하지만 특정 데이터베이스에 종속적인 기능은 지원하지 않는다. 예를 들어 다음과 같은 것들이다.
* 특정 데이터베이스만 지원하는 함수, 문법, SQL 쿼리 힌트
* 인라인 뷰(From절에서 사용하는 서브 쿼리), UNION, INTERSECT
* 스토어드 프로시저 
  <br>
  
때로는 특정 데이터베이스에 종속적인 기능이 필요하다. JPA는 특정 데이터베이스에 종속적인 기능을 사용할 수 있는 다양한 방법을 열어두었다.

* 특정 데이터베이스만 사용하는 함수
* 특정 데이터베이스만 지원하는 SQL 쿼리 힌트
* 인라인 뷰(From 절에서 사용하는 서브쿼리), UNION, INTERSECT
* 스토어 프로시저
* 특정 데이터베이스만 지원하는 문법
 <br>
 다양한 이유로 JPQL을 사용할 수 없을 때 JPA는 SQL을 직접 사용할 수 있는 기능을 제공하는데 이것을 네이티브 SQL이라 한다.

