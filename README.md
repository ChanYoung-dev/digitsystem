# 목표
- 사료를 자동으로 공급하고 공급한 뒤 일정시간 뒤에 공급하는 자동사료급여기  
  ① 초음파 센서로 디지털 값을 받는다.    

  ② 디지털 값으로 받은 사료의 양을 LED로 표현한다.  
  (초음파 센서의 값이 적으면 사료가 꽉찬 것이므로 LED8개가 켜진다.)  
  ③초음파 센서값이 늘수록 사료를 먹어가는 것을 확인할 수 있다.  
   (LED가 줄어든다.). 
  ③사료의 양이 줄어들어 LED값이 0이 되면 FND에 카운트가 실행된다
  ④카운트 출력이 완료가 되면 Motor가 실행되어 사료를 공급한다.  
  ⑤LED값이 채워지고 사료를 먹어서 초음파센서거리가 가까워지면 다시 반복한다!   

