redirect

- 2 번 요청, 2번 응답
- GET 방식(자동요청)

forward

- 1 번 요청, 1번 응답
- 전달

request에 값을 저장해서 사용할때는 forward를 사용한다.

HTTP 요청과 요청 방법 요약 정리

1. URL 직접 입력으로 요청(GET)
2. 링크 <a>로 요청(GET)
3. 폼<form>으로 요청(GET, POST)
4. redirect - 다른 URL로 이동(GET), 자동 재요청. 브라우져 URL 변경됨 - 요청/응답 2번
5. foward - 요청(GET, POST)을 다른 URL로 전달. 브라우져 URL 변경 안됨
