# BMS based on Linduino
 포터 학회 활동에서 작성 및 수정한 BMS 코드 
 Linduino를 기반으로 하였으며 오픈소스를 참고함
# 변경 및 추가 사항
## 2021.01.18
* LED제어문 (10~13번 핀은 SPI 통신을 쓰기에 초기에 13번 핀 LED 제어가 불가능 했었다.)
* VOV(Voltage Over Voltage), VUV(Voltage Under Voltage)에 따른 Flag 값 출력문 수정 
* 12개의 cell 각각의 voltage 값 출력 
## 2021.02.03
* GPIO(General Purpose Input Output) 핀 중 5번에 납땜을 하였지만 값이 읽히지 않았음
* 추가 요구 사항 
* 1. DCC 제어문 (Discharge Cell)
* 2. 배터리 상태 값을 5분 간격으로 출력 
