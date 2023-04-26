- SQL 쿼리 실행 순서
  ```mysql
  FROM - WHERE - GROUP BY - HAVING - SELECT - ORDER BY
  ```
  - FROM 절에서 전체 테이블의 결과를 가져옴
  - WHERE 절에서 조건에 맞는 결과를 가지도록 분류
  - GROUP BY 절에서 선택한 열로 묶음 작업
  - HAVING 절에서 추가적인 조건 처리
  - SELECT 절에서 남은 데이터 중 어떤 열을 출력할 지 선택
  - ORDER BY 절에서 행의 출력 순서를 정리

- SQL VS NoSQL
  |구분|SQL|NoSQL|
  |---|---|---|
  |스키마|O|X|
  |관계|O|X|
  |유연성|⬇|⬆|
  |확장성|수직|수평|
  
  