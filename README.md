# AuLora
SETALab
AuLoRa
오로라 사용을 위해서는 온라인 라이센스 구매가 필요합니다.

Contact :  www.setalab.com help@setalab.com

오로라를 이용한 로라 기술 교육 동영상:

https://youtu.be/MoPm72SUUzI

 https://youtu.be/bTfFbvgL5HY

------------------------------------------------------------------
AuLoRa 1.2.2 버전 업데이트 2021. 09. 16
* DevGetATCmd 사용시 2초가 기다리면서 데이터를 받도록 수정

------------------------------------------------------------------
AuLoRa 1.2.1 버전 라이센스 서버IP 및 포트 업데이트 2021. 06. 28

------------------------------------------------------------------
AuLoRa 1.2.1 버전 업데이트 2019. 04. 08

rx end character가 only LF인 경우에도 로그에 표시되게 수정

------------------------------------------------------------------
AuLoRa 1.2.1 버전 업데이트 2018. 12. 11

Freq Set/Get 하기

Tx Power level 0~ 14 Set 하기

rssi, snr 값 가져오기

CFList 0일때 초기화 안되는 문제

port = 0 일때는 nwkskey로 암호화

Real App key 초기화 안되는 문제 수정

여러 단말에서 보낸 데이터로 인해 Down 메시지 전송 안되는 문제


------------------------------------------------------------------
AuLoRa 1.2 버전 업데이트 2018.7.12

data가 200개가 넘을 경우 heap 오류 수정

txpk tmst dword -> double로 확장 ( 4byte -> 8byte)

log save 기능 추가

data가 200개가 넘을 때 버퍼 오류 수정

인증 루틴 수정 (온라인 -> 오프라인)

RX1 windowdelay 오류 수정

RX2 Down API 추가

Class C 지원

DR5 max data down 오류 수정


------------------------------------------------------------------
AuLoRa 1.1 버전 업데이트

인증 서버 변경

로그 레벨 변경 API 추가 : SrvSetLogMode(loglevel); // 0 : all, 1: correct data ony, 2 : correc data + MIC error

Down FCnt 설정 API 추가: SrvSetParam("DOWNFCOUNT", "005A"); // 0x005A

Log file save 기능 추가

Mac Command Hexa 처리 오류 수정

