# Statistics

### 통계학은 기술 통계학, 추측 통계학, 베이즈 통계학으로 나뉜다.
+ 모든 데이터를 조사 그래프화, 평균, 분산하는 __기술 통계학__
+ 2개 이상의 변량 데이터를 다루는 __다변량분석__ (회귀분석, 인자분석, 주성분분석, 판별분석, 클러스터분석, 수량화 이론)
+ 일부 표본을 이용하여 추측 정규분포곡선을 자주 사용(추정->가설검정)하는 __추측 통계학__
+ 주관적 확률, 인간의 경험도 사용하는 __베이즈 통계학__ (베이즈 확률, 베이즈 추론, 베이즈 결정)

+ 'Garbage in Garbage out' 쓰레기 데이터에서는 쓰레기와 같은 결과만 나온다. 의미 없는 데이터는 분석해도 전혀 도움이 되지 않는다.

## 기술 통계학
1. 대상이 되는 '집단'이 하급이나 회사와 같이 비교적 작고 __전체 데이터를 모으기 쉽다.__ 
2. 해당 데이터를 이용하여 그래프를 만들고 데이터를 시각화(기술)한다.

#### 세 종류의 대푯값
+ 평균
> 전체의 수를 더하고 이를 데이터 수로 나눈 값, 데이터 전체의 중심에 해당
+ 중앙값
> 데이터를 작은 값부터 순서대로 나열했을 때 한가운데 위치에 있는 값
+ 최빈값
> 데이터 중에서 가장 많이 나타나는 값

#### 산포도
> 데이터의 폭이나 흩어짐의 상태

1. __분산(표준편차)__
> 데이터의 흩어짐 정도를 나타내는 값 중 하나, 분산(variance)과 표준편차(stand-and deviation)는 원래 같은 내용이므로 거의 동의어로 사용함(값은 다름)

2. __사분위범위__
> 1/4 위치에 있는 값인 제1 사분위수(25번째 백분위수), 3/4 위치에 있는 값인 제3 사분위수(75번쨰 백분위수)까지의 폭을 말함, 중심 근처의 데이터 흩어짐 정도를 보는 지표, 덧붙여 제2 사분위수는 중앙값과 같다(유의어 __IQR__ )

3. __범위__
> 데이터가 위치하는 폭(최대-최소)을 나타내는 값


## 추측 통계학
+ 엄청나게 큰 데이터(모집단)이라면 모든 데이터를 얻지 못할 수도 있다. 이럴 때 강력한 도구가 추측 통계학이다.

__가설검정__
1. __거짓이라 생각하는 가설을 일부러 세움.__
2. __데이터를 이용하여 거짓이라 생각하는 가설을 판단/기각__


+ __모집단__
> 대상이 되는 모든 데이터를 통계학에서는 __모집단__ 이라고 부른다.

+ __표본__
> 모집단에서 뽑은 샘플데이터를 __표본__ 이라 부른다.

+ __추정__
> 소수의 표본 데이터에서 전체 집단(모집단)의 특징을 추측

+ __가설검증(검증)__
> 전체 집단에 대해, 특정 가설의 검정을 일정 확률로 검정

#### 다중응답과 단일응답
    다섯 개의 선택지가 있는 설문이 있다고 할 떄 '하나만 선택'하는 것을 단일응답방식이라고 한다.
    다중응답 설문에서는 원그래프 사용 금지, 막대 그래프 사용
   
## 다변량분석
> 2변량(변수) 이상을 다루는 분야


### 연속량 데이터와 비연속량 데이터
+ 연속량 데이터
> 두 값 사이에 무수히 많은 값으로 이루어진 이어진 점으로 표현할 수 있는 아날로그식 데이터

+ 구분법
- 연속량, 비연속량 구분은 __소수점 이하__ 인 수치가 있는지 없는지로 판단.

+ 비연속량 데이터
> 서로 이어지지 않고 띄엄띄엄 흩어진 수인 이산 데이터


#### 척도로 데이터 분류
+ 데이터는 질적 데이터와 양적 데이터로 나뉜다.
+ __질적 데이터__
1. 명목척도: 수치 데이터를 부여하여 통계적으로 처리 ex) 성별, 주소, 혈액형, 찬반 (최빈값만 사용)
2. 서열척도: 순서에 따라 우열 또는 크고 작음의 순서를 알 수 있는 데이터 ex) 성적순(1등,2등..),평가(좋고 싫음) 등 (중앙값, 최빈값 사용가능)
+ __양적 데이터__
3. 등간척도: 온도계의 온도와 같이 각각의 눈금 간격이 같은 데이터를 말함. ex) 체온, 기온, 득점 등
4. 비율척도: 4가지 척도 중에 가장 다루기 쉬운 데이터 ex) 키, 몸무게, 돈, 시간 수입, 연령 등

4 > 3 > 2 > 1로 4가 통계에서 가장 사용하기 쉽다.
