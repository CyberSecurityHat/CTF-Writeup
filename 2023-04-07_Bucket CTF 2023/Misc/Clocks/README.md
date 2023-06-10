# Detective

### 난이도 : Normal

##### 문제 풀이

1. 문제가 clocks인 것을 통해 시간 관련 문제인 것을 추측 가능
2. wireshark에서 왼쪽 아래 패킷 상세 뎅이터에서 Frame을 펼쳐보면 Time delta from previous captured frame 확인 가능
    - 0.1... seconds : 0
    - 0.5... seconds : 1
3. 각 초를 각 이진수로 변환 후 해당 이진수를 아스키코드로 변환하면 플래그 획득 가능