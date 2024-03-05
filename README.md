# SchoolZone_Accidents_EDA

EDA on the accident data in child protection zones in Seoul from 2018 to 2020

### 1. Various factors related to the number of accidents and the number of victims (사건건수와 피해자수에 대한 다양한 요인).
   
 ![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/9f9300f8-8cb7-4313-852d-c29696bd37e0)
 - 평일 대비 주말의 적은 피해자수
 - 더운 여름 6,7,8월에 비교적 피해자수가 많다. 또한 12월도 두드러짐 (왜???)
   
![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/555bea44-0783-431b-bbd0-c4fb5449e165)
 - 어린이 주 생활시간인 8시~ 19시에서의 발생이 잦으며, 특히 등하교 시간인 8시와 15 ~ 16시가 주변에 비해 두드러지게 증가한것을 확인
   
![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/f42fb231-4018-4047-a439-737ea294d386)
- 노면상태와 기상상황을 살펴보면 대부분의 날씨가 맑은날이였고 따라서 건조한 노면상태인 날이 대부분임.

![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/d17e3e7d-b0e6-4288-9200-36f5f36b7b92)
- 성북구, 도봉구, 강서구 순서대로 어린이보호구역내 사고가 많았음을 확인
- 구별 인구데이터, 학교 수 데이터 등 외부 데이터와의 연계확인 필요.

### 2. Various factors based on accident types (사고유형에 따른 다양한 요인).
   ![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/9683d1b0-f273-4b1b-bedb-ec42ce54da7a)
   - 상해정도에 따른 사고유형을 통해 어린이 보호구역 내에서의 사고 상해는 대부분 경상이였다.
   - 경상을 차지하는 가장많은 부분은, 차대차 사고의 경우이다.
   - 사고유형별 상해정도를 보면, 차대차사고의 경우 대부분이 경상이거나 상해없음으로 상해의 정도가 낮음을 확인 가능하다.

### 3. Victim ratios based on age (나이에 따른 피해자 비율).
![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/c2f9fb0c-5940-4052-9580-d9dd91f96533)
- 어린이 보호구역이라, 피해자가 어린이가 많을 것이라고 예상하였지만, 66.3%가 성인, 청소년이 3.5%, 어린이는 30.1%
- 피해비율이 청소년피해자 보다 어린이피해자가 약 9배정도 많이 발생되었다.

### 4. Various factors based on gender (성별에 따른 다양한 요인).
![image](https://github.com/2hy03/SchoolZone_Accidents_EDA/assets/101242683/36f623f5-4336-498e-8b92-8cefe54abda7)
- 성별에 따라 살펴볼때 여성가해자가 남성보다 적음에 남성운전자 수가 많기 때문이라고 예측 가능하다.

- 전체 사고수에 성별의 영향을 어떻게 받았는지 확인
  - 6~8월의 전체 사고수는 여성의 사고증가의 영향을 많이 받았다.
  - 12월의 전체 사고수는 남성의 사고증가의 영향을 많이 받았다.
