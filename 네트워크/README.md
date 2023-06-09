- http 메소드 비교
  - GET : 특정 리소스의 표시를 요청, 데이터를 받는 데 사용
  - POST : 특정 리소스를 생성, 서버에 데이터를 보내는 데 사용
  - PUT : 특정 리소스를 업데이트, URL을 보내지 않아도 됨
  - DELETE : 특정 리소스를 삭제

- http 주요 응답 코드
  |상태|코드|설명|
  |---|---|---|
  |정보 응답|100 Continue|요청의 상태가 정상적이며, 이후 정보를 추가로 요청함|
  |성공 응답|200 OK|요청이 성공적으로  전송됨|
  ||201 Created|요청으로 인해 새로운 정보가 생성됨|
  ||202 Accepted|요청을 수신했지만 그에 응하는 행동을 하지 않음|
  ||204 No Content|요청에 대해 보내줄 정보가 없음|
  |리다이렉션 메시지|301 Moved Permanently|요청한 리소스의 URL가 변경됨|
  |클라이언트 에러|400 Bad Request|사용자의 요청이 잘못됨|
  ||401 Unauthorized|페이지에 대해 사용자 인증이 필요함|
  ||403 Forbidden|인증된 사용자가 접근 권리를 가지고 있지 않음|
  ||404 Not Fount|요청한 리소스를 찾을 수 없음|
  |서버 에러|500 Internal Server Error|서버가 요청 처리 방법을 모름|
  ||501 Not Implemented|서버에서 지원하는 요청 방식이 아님|
  ||502 Bad Gateway|게이트웨이*로 작업하는 동안 잘못된 응답이 수신됨|
  
  *게이트웨이 : 서로 다른 종류의 네트워크간의 통신 프로토콜을 변환

- http와 https의 차이
  |구분|http|https|
  |---|---|---|
  |보안성|⬇|⬆|
  |속도|⬆|⬇|
  |비용|⬇|⬆|
  