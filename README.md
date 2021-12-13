# 부산시 남구 주차장 최적입지 선정

# Description
QGIS기반 부산시 남구 주차장 최적 입지 선정

## 분석개요
주차난 해소에 따른 사회적 편익증가 
서울시 기준 연간 불법 주차로 인한 사회적 비용 약1323억원, 불법주정차로 인한 차대차 사고 비용 약435억원, 불법 주차로 인해 골든타임 증가로 인한 잠재적 사회적 비용 약 62.5억원


## Data
![image](https://user-images.githubusercontent.com/79688191/145759285-40531595-1b04-454b-b4e1-245f2a78af06.png)

### 부산시 남구 건축물 대장 [CSV]
![image](https://user-images.githubusercontent.com/79688191/145759509-1467f3db-44d5-4b9a-aaa0-6ea3893b0bd6.png)

![image](https://user-images.githubusercontent.com/79688191/145759529-92e722bd-e46c-4413-ab3d-4c1a0815ab49.png)


## 분석process 

<img src="https://user-images.githubusercontent.com/79688191/145759577-7935f88f-6c04-4680-ba00-971d1b86e130.png" width="800" height="200"/>


### 회귀분석
다중공선성 검정 및 회귀분석

![image](https://user-images.githubusercontent.com/79688191/145759678-e564ed5c-becc-4dd9-974f-fc0143f52160.png)

### Python 활용 
1. 위경도.py 도로명주소 기반 위경도 주소 추출
2. 교통량.py 부산시 api 활용 교통 정보 추출
3. 우선순위.py 각 격자 별 주차 수요 우선순위 산출
                                                                                                                                         
<img src="https://user-images.githubusercontent.com/79688191/145759695-e30ca5cd-7d24-44eb-b444-7cd0a087000f.png"  width="600" height="200"/>
                                                                                                                                         
### QGIS 기반 시각화
<img src="https://user-images.githubusercontent.com/79688191/145760501-fabf86fa-156e-4dd5-a4d4-c9446ac939d0.png" width="600" height="200"/>

![image](https://user-images.githubusercontent.com/79688191/145760930-21c528db-dc71-46e5-846c-62b6af4366e5.png)
![image](https://user-images.githubusercontent.com/79688191/145760939-445f5615-fd93-4811-a6cc-329cf3d745b6.png)





# Usage
### result 
 분석 보고서, ppt, QGIS 실행 파일, 분석 결과 excel 파일

### Data
 사용 데이터

### code
 python code
1. 위경도.py 도로명주소 기반 위경도 주소 추출
2. 교통량.py 부산시 api 활용 교통 정보 추출
3. 우선순위.py 각 격자 별 주차 수요 우선순위 산출
