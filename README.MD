참고자료 : https://socket.io/docs/v4/load-testing/

부하테스트 실행 명령어 artillery run socketio-config.yml --plugin socketio-v3

구성 섹션  
 테스트이 총 기간 (60초) duration: 60
사용자 arrivalRate: 10

시나리오 섹션

1초 동안 일시정지 think: 1
