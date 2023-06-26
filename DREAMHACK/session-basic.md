app.py 문제 파일을 잘 보면 id admin의 비밀번호가 flag인 것을 알 수 있다.
또한, path 중에 /admin 이 있는 것을 알 수 있다.
문제 사이트 url 뒤에 /admin 을 입력하여 들어가면 admin의 session이 나온다. 
이것을 복사 한 뒤에, F12를 눌러 관리자 도구 Application 에서 해당 사이트의 Cookies에 들어간다. 
그리고 Name 을 더블 클릭하여 sessionid 를 입력하고, Value에 아까 복사한 session를 붙여넣기하고 새로고침하면 admin id에 따른 flag를 찾을 수 있다.
