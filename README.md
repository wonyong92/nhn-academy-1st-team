# shttpd 만들기
---
- 개요 : python 에 SimpleHTTPServer 라는 모듈이 있습니다. 유사한 프로그램을 작성합니다.
- 구현 기능

  1. 포트번호 인자로 받아 실행
  2. 포트번호를 listen. 멀티세션은 선택?
  3. 실행된 디렉토리를 루트로 지정 - 요청에 대한 String parsing 필요
  4. GET METHOD 구현
  5. POST( + Multipart/form-data ) METHOD 구현
  6. DELETE METHOD 구현

- Status Code

  1. 403 
