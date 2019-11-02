# HW2: Deep Feedforward Neural Networks
Data: Ablone.csv<br>
문제: 전복 데이터<br>
분류 Target: 전복의 성별(M/F/I)<br>
<br>
변수: 총 8개<br>
 Name  Data Type Meas. Description<br>
  ----  --------- ----- -----------<br>
 Sex  nominal   M, F, and I (infant)<br>
  Length  continuous mm Longest shell measurement<br>
  Diameter continuous mm perpendicular to length<br>
  Height  continuous mm with meat in shell<br>
  Whole weight continuous grams whole abalone<br>
  Shucked weight continuous grams weight of meat<br>
  Viscera weight continuous grams gut weight (after bleeding)<br>
  Shell weight continuous grams after being dried<br>
  Rings  integer   +1.5 gives the age in years<br>
<br>
## Requirement:
1. Data를 train:test로 분할한다.
2. 변수 정규화를 실행한다. (sklearn.preprocessing.MinMaxScaler 사용)
2. Sklearn을 이용해서 Classifier A를 만든다(예제와 다른 옵션 사용).
3. keras를 이용해서 Classifier B를 만든다(예제와 다른 옵션 사용).
4. A와 B의 test data에 대한 accuracy를 비교한다. 
