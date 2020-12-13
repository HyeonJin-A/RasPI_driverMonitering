#driver monitering system


1. 라즈베리파이에 연결된 카메라를 통해 운전자의 얼굴을 실시간으로 캡처
2. 눈 크기를 계산
3. 눈이 감겼다면 카운트+
4. 카운트가 일정 수치를 초과하면 경고음 재생
<div>
  <img height="250" src="https://user-images.githubusercontent.com/75927764/102011686-3c838c00-3d89-11eb-89f0-243b3f38121b.jpg">
  <img height="250" src="https://user-images.githubusercontent.com/75927764/102011689-41e0d680-3d89-11eb-9fe9-7309803daffe.jpg">
</div>

이후 기능을 추가하여
ios 앱을 통해 알람음 조정이 가능하도록 만들었다.
리소스에는 없다.


<img width="200" src="https://user-images.githubusercontent.com/75927764/102011691-44dbc700-3d89-11eb-86af-321f564337f4.jpg">
 

실행방법 (카메라가 연결된 기기에서)
python Drowsiness_Detection.py
