# Auto-parking-line-tracer

자율주차 로봇  
  
2대의 카메라를 사용합니다.  
  
1. 전방의 카메라는 라인을 검출합니다.  라인이 이미지 중앙에 오도록 모터를 제어합니다.

![전방2](https://github.com/rkskwhdgh123/Auto-parking-line-tracer/assets/103232943/528d2c71-022a-4bac-9454-1a6924c9a2c4)



      
2. 우측 카메라는 코너를 검출합니다.  코너가 찍히는 점으로 주차 가능 영역인지 판단하고 정지합니다.  

![우측2](https://github.com/rkskwhdgh123/Auto-parking-line-tracer/assets/103232943/3203ea42-1a41-4172-8289-73184af200b1)





        
3. 로봇을 회전하면서 이번에는 전방카메라가 코너를 검출합니다.  주차영역을 발견하면 진입하여 주차를 완료합니다.


![33](https://github.com/rkskwhdgh123/Auto-parking-line-tracer/assets/103232943/0fe58f6d-3e67-4228-b1ff-e5568d5c4ef8)


YouTube 영상 첨부
https://www.youtube.com/watch?v=bucoBzZqgB0&t=47s
