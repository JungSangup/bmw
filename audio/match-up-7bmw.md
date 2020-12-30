# MATCH UP 7BMW









## Automatic Time Measurement – ATM

https://www.audiotec-fischer.de/en/knowledge-base/DSP-PC-Tool/atm/



정확한 스테이지 이미지를 위해 타이밍 조정이 필요함.

스피커와 운전자간 거리 실측을 통한 방법도 유효하나, 측정오차에 의한 잘못된 설정이 될 수도 있음. 특히, Passive 2-Way 시스템의 경우 더욱 측정이 어려움.

ATM은 이러한 복잡하고 어려운 타이밍 설정을 자동화해 주는 DSP PC-Tool의 기능임.



### 준비사항

아래 사항에 대한 점검이 필요함. 만약, [Audiotec-Fischer](https://www.audiotec-fischer.de)에서 제공하는 [셋업파일](https://www.audiotec-fischer.de/en/matchdatabase/soundIndex)을 적용했다면 특별히 변경할 것은 없고, 측정 마이크의 위치만 정확히 고정.

![IO_Menu](./img/IO_Menu.PNG)

- 출력채널 이름 확인 (eg. Front L Full)

- 미사용 채널은 'Not Used'로

- 미드레인지와 트위터는 High pass filter를 설정할 것!

- 측정 마이크의 위치는 운전자 머리 중앙에 위치하도록 설치. (아래 그림과 같은 위치)

  <img src="./img/microphone.PNG" alt="microphone" style="zoom:50%;" />

### 테스트 음원

{DSP PC-Tool 설치 디렉토리}/soundFiles/ATM - Automatic Time Measurement/timeMeasurementClick.mp3파일(또는 timeMeasurementClick.wav 파일)을 USB Stick에 복사하여 준비. 

> 위의 디렉토리는 DSP PC-Tool 실행 후 우측 메뉴 중 "Test Tones" 를 통해서도 접근 가능.

<img src="./img/Test_Tones.PNG" alt="Test_Tones" style="zoom: 67%;" />

### Input 설정 (Source of the test signals)

 광케이블이나 별도의 Extension Card(HEC)를 통한 재생이 아닌 일반적인 경우 Analog(Line- or Highlevel Input) 로 설정. (Default : Analog)

> 참고 : Head-unit to DSP Pin config. (System connector 1의 1~4, 11~14)

![Pin_config](./img/Pin_config.PNG)

### 레퍼런스 스피커

ATM은 레퍼런스 스피커와 다른 스피커간의 차이(Time delay)를 이용하여 자동 측정하는 기능이며, 이를 위해 하나의 레퍼런스 스피커를 지정해주어야 함.

Front Left 를 레퍼런스 스피커로 설정 (좌핸들인 경우 자동 선택)

### 측정 모드 설정

Distance Mode 를 선택하고, 레퍼런스 스피커와 마이크사이의 거리를 측정하여 기입

### 측정

테스트 음원을 실행하고, ATM 창의 Audio Input 바가 **Good** 위치에 오도록 볼륨을 설정한 뒤, **Start** 버튼을 클릭하여 측정 시작

