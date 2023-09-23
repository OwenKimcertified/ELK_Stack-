# ELK_Stack (logging)
Elastic search, Log stash, Kibana 

1. server 의 log file 을 Beat 로 저장

2. server 의 log 관련 config 가 변경되었을 때 각 서버에 ssh 접속으로 하나하나 config 를 수정하지 않고 log stash 로 파싱 
  - server 가 매우 많다면 ES 에 stack 하기 전 Kafka 를 추가해 Kafka 먼저 보내 부하를 줄임 and HA 를 가능하게 하기

3. elastic search 에 stack

4. stack 된 data 를 kibina 에서 확인 or dashboard

관련 내용들을 정리합니다. 

docker 환경에서 진행하며 설치는 https://github.com/deviantony/docker-elk 에서 클론하시고 내용을 보며 설치하시면 됩니다.

![스크린샷 2023-09-23 15-03-54](https://github.com/OwenKimcertified/ELK_Stack/assets/99598620/36a4964c-b2e0-462f-b60b-c6ba182a28af)
