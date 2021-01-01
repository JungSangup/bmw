# Coding



## Installation

- **E-Sys Launcher PRO V2.8.1.155** ( /w TokenBuster)
- **E-Sys 3.28.1**,  E-Sys 3.30.1
- PSDZ Data Lite V4.22.41 , **PSDZ Data Lite V4.27.11**
- 접속코드 : **S15A**
- Firmware version : S15A-18-07-521 , **S15A-20-11-542**



## Execution (작성 중)

### E-Sys Launcher  PRO 실행

관리자 권한으로 실행 후 아래와 같이 설정

- Location : E-Sys 설치 디렉토리
- List : 설치된 E-Sys 를 추가(+)
- EST Path : est_token.est 의 경로를 지정
- PIN
- Memory : 가능하면 크게...
- FDL Cheat Codes : 사용할 Cheat code를 선택 ( 경로는 {E-Sys Launcher PRO 설치 디렉토리}/FDLCodes )
- High Resolution Fix : 고해상도 디스플레이에서 글자가 겹쳐지는 현상 방지

![image-20210101151251269](./img/E-Sys_Launcher.PNG)

> 실행 중 메모리 관련 에러 (C150) 발생 시 Memory 설정을 변경해 볼 것! (Ex. Custom 1150MB)

위와 같이 설정 후 **Launch Now** 버튼을 클릭하여 E-Sys 실행.

메인화면 좌측 메뉴에서 Export Mode > Coding 선택 후 상단 연결아이콘 클릭

![E-Sys_1](./img/E-Sys_1.PNG)



연결설정 창에서 Target (S15A_xx_xx_xxx) 선택 , Connection via VIN 선택 후 **Connect** 버튼을 클릭하여 연결

![E-Sys_2](./img/E-Sys_2.PNG)



Vehicle Order (왼쪽 위) 에서 **Read** 버튼 클릭 후 FA List 가 표시되면, 아래 FA를 선택하고 마우스 우클릭 후 

**Activate FA** 클릭

![E-Sys_3](./img/E-Sys_3.PNG)



Vehicle Profile 에 항목들이 표시되면, 아래 SVT Actual 에서 **Read (ECU)** 버튼을 클릭하면 왼쪽아래 SVT 영역에 ECU 트리가 표시됨.

![E-Sys_4](./img/E-Sys_4.PNG)







## 재난안전문자 비활성화


HU_NBT : head unit -> expert mode -> 3002 audio_tuner_traffic -> ews_korea -> nicht-aktiv
