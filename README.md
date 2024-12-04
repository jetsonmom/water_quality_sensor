# water_quality_sensor
######  for arduino
<b> https://randomnerdtutorials.com/arduino-tds-water-quality-sensor/

![image](https://github.com/user-attachments/assets/4523b2d5-5f50-4a8c-9aba-296db01de5d8)

![image](https://github.com/user-attachments/assets/43bc17bb-da63-4ef3-b495-1b9433d16816)
https://www.linkedin.com/pulse/httpsgithubcommcortsm5stickcphsensor-m-carlos-orts-garc%C3%ADa/

![image](https://github.com/user-attachments/assets/57f30d09-c74f-482b-b804-505bb168da88)

![image](https://github.com/user-attachments/assets/558c302c-fbcf-4370-9460-36cc3162f0a6)


<b> 
이미지를 보니 이것은 온도 센서의 연결도이며, 특별한 접지 상황을 설명하고 있습니다.

센서의 GND를 연결할 때 두 가지 방법이 있습니다:
![image](https://github.com/user-attachments/assets/b89449ad-d75b-450c-812e-574755bd9019)

1. 기본 연결 방법:
- Jetson Nano의 GND 핀(6, 9, 14, 20, 25, 30, 34, 39 중 하나)에 직접 연결

2. 측정 대상(액체)이 다른 전기적 접지를 가질 경우:
- 측정하려는 액체/물체의 접지점에 연결
- 이는 측정 대상이 다른 전기 시스템과 연결되어 있거나 독립적인 전기적 특성을 가질 때 필요합니다

이미지에서 보이는 특별 참고사항:
- "ground voltage of the liquid to measure is different"라는 설명은 
- 측정하려는 액체가 독립적인 접지 전압을 가질 수 있음을 의미합니다

추천하는 방법:
1. 먼저 Jetson Nano의 GND에 연결해서 테스트
2. 만약 측정값이 불안정하거나 부정확하다면
3. 측정하려는 액체/시스템의 접지점에 연결해보기

