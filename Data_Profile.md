# Data Profile

###### 요약 

1. 총 26049 row, 6columns
2. null 값이 없다!

###### Columns 설명

* id: 각 개인의 고유한 ID


* age : 나이
  * 17세에서 90세까지
  * 누운 호리병 모양의 분포를 보여줍니다.
  
  
* workclass : 고용 형태
  * 총 9개의 고용 형태입니다.
    * Private: 자영업, 18123명, 69.6%	 
    * Self-emp-not-inc: 법인 없는 개인 사업가, 2030명, 7.8%	 
    * Local-gov: Local 정부 소속, 1692명, 6.5%	 
    * ?: 직업 알 수 없음, 1502명,	5.8%	 
    * State-gov: State 정부 소속, 1043명, 4.0%
    * Self-emp-inc: 법인이 있는 개인 사업가, 877명, 3.4%	 
    * Federal-gov: Federal 정부 소속, 765명,	2.9%	 
    * Without-pay: 돈 안 받음.., 11명, < 0.1%	 
    * Never-worked: 일 안 함, 6명, < 0.1%
    
    
* fnlwgt : 사람 대표성을 나타내는 가중치 (final weight의 약자)
  * 사후 층화 가중치, 한 표본이 몇 개를 대표하는지 의미합니다. 
    (e.g. 모집단의 남녀 비율이 45%,55%인데 표본에서 60%,40% 일 경우 가중치를 주어 조정을 해줍니다.)
  * 값이 168538 일 경우, 이런 특성 가진 사람이 168538명 있다 라는 의미
  * 최솟값 ~ 최댓값 (13769 ~ 	1484705)
 
 
* education : 교육 수준
  * 총 16개의 교육 수준을 나타냅니다.
    * Bachelors(4년제학사)
    * Some-college(전문대)
    * 11th
    * HS-grad
    * Prof-school
    * Assoc-acdm 
    * Assoc-voc 
    * 9th
    * 7th-8th
    * 12th
    * Masters
    * 1st-4th
    * 10th
    * Doctorate
    * 5th-6th
    * Preschool
  
  
* education_num : 교육 수준 수치 (교육 받은 햇수)
  * education을 친절하게도 햇수로 표현했습니다.
  * 높을 수록 교육을 오래 받았습니다.
  
  
* marital_status: 결혼 상태
  * Married-civ-spouse: 기혼,	11970명,	46.0%	 
  * Never-married: 미혼, 8568명, 32.9%	 
  * Divorced: 이혼, 3536명, 13.6%	 
  * Separated: 별거(법적 별거, 결혼 불화, 이혼 직전 등), 826명, 3.2%	 
  * Widowed: 사별, 796명, 3.1%	 
  * Married-spouse-absent: 별거(직업 등의 사유로), 334명,	1.3%	 
  * Married-AF-spouse: 별거(군인), 19명,	0.1%


* occupation : 업종(직업)
  * 총 15개 업종
  * Tech-support(기술자), Craft-repair(기능공), Other-service(제3서비스업), Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.


* relationship : 가족 관계
  * Husband: 남편	10541	40.5%	 
  * Not-in-family: 가족없음	6632	25.5%	 
  * Own-child: 자녀 4099	15.7%	 
  * Unmarried: 결혼 안 함	2740	10.5%	 
  * Wife: 아내	1260	4.8%	 
  * Other-relative: 그 외 관계	777	3.0%


* race : 인종
  * White	22315	85.7%	 
  * Black	2476	9.5%	 
  * Asian-Pac-Islander	800	3.1%	 
  * Amer-Indian-Eskimo	254	1.0%	 
  * Other	204	0.8%	


* sex : 성별
  * Male	17482	67.1%	 
  * Female	8567	32.9%


* capital_gain : 양도 소득, 자본 소득
  * 0에서 99999 까지 인데 추가 확인 필요


* capital_loss : 양도 손실
  * 0에서 4356


* hours_per_week : 주당 근무 시간
  * 1시간에서 99시간까지


* native_country : 국적
  * 총 41개국
  
  
* income : 수익 (예측해야 하는 값)
  * 50K 이하	19744	75.8%	 
  * 50K 초과	6305	24.2%