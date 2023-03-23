# infinite_scroll

# 로직
1. 스크롤이 발생 했을때 scrollHeight - offsetHeight - scrollTop 이 내가 정한 offset보다 작다면 api를 이용해서 데이터를 가죠온다.
2. 마지막 데이터까지 가져오면 api요청을 막아야하낟.
# 알게된점
## overflow
https://velog.io/@toyo8/overflow-%EB%9E%80
## useRef 실무기능
https://velog.io/@toyo8/useEffect-%EB%9E%80
