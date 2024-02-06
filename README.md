# 프로젝트의 목적
###### 메가서울 : 메가서울의 모델인 메가시티는 핵심 도시를 중심으로 주변 지역과 교통·경제·문화를 연결한 인구 1000만 명 이상의 거대 도시 권역을 뜻한다.
<br>

- 서울 메가시티 통합 발표 후 부동산 투자에 관심을 갖는 모든 자본이 이목을 집중하고 있다.
- 정책으로 인해, 부동산 가격 상승의 직접적인 수혜를 받게 될 것이라고 예상되는 김포시 및 서울 주변 지역 거주민들은 서울 외곽의 거주민들보다 정책에 대한 기대감이 높다.
- 하지만 김포시와 서울시의 부동산 시장에, 정책이 끼치는 영향은 미미하다라고 보는 시각 또한 존재한다.  
- 본 프로젝트는 김포시와 서울시의 부동산 시장 데이터를 활용하여 부동산 시장 동향을 시각화하고, 
<br>부동산 시장에 대한 분석과 해석을 제공하여 사용자가 부동산 투자 결정을 하는 것에 도움을 줄 수 있는 대시보드를 개발하는 데 목적을 둔다. 
<br>이를 통해, 사용자는 김포시와 서울시의 부동산 시장 가격 변동과 거래량을 한 눈에 파악 할 수 있고, 부동산 시장에 대한 인사이트를 제공받는다. 
<br>이로 인해, 사용자는 김포시와 서울시의 부동산 시장을 쉽게 파악하고 부동산 투자 결정을 내리는 데 도움을 받을 것이다.

<br>

## 팀원 소개
#### 분석팀
  - 정혜원(팀장) : 깃허브 주소~
  - 이형주 : 깃허브 주소~
#### 개발팀
  - 김영기 : 깃허브 주소~
  - 최진혁 : 깃허브 주소~
#### 기획팀
  - 안 별 : 깃허브 주소~
  - 송인동 : 깃허브 주소~

<br>

## 본 프로젝트에서 사용한 주요 개발환경 요약 
  + Programming Languages : Python(ver. 3.11.7)
  + Web Framework : Streamlit, Jupyter lab

## 주요 라이브러리 버전
  + Pandas, Plotly.express , Numpy

## 데모페이지
- Streamlit에서 구현한 Demo는 다음과 같습니다.
  + https:// 배포된 주소 .streamlit.app/

 ## 주요 기능
 - 본 프로젝트에서 활용한 주요 메서드는 다음과 같습니다.

```python
#데이터 전처리
Pd.read_csv() #데이터파일을 불러옴
Dataframe.to_csv() #전처리된 데이터파일을 내보냄
loc() #우리가 원하는 행과 열을 뽑을 때 사용
pd.cut() #연속적인 데이터를 범주형으로 묶어줄때 사용
Dataframe.assign() #데이터프레임에 새로운 열과 그안의 값을 넣어줄 때 사용

#각각 반복문을 통해 str 포메팅 사용
sort_values() #우리가 기준으로 잡는 열에 맞춰 순서대로 나열해줌
.astype() #데이터의 자료형을 변환시켜줌
groupby().unique() #우리가 원하는 series의 고유값들을 출력해줌
pd.concat() #전처리 해놓은 데이터를 합칠 때 사용

#시각화
#Plotly.express 사용
Px.bar() #매개변수로 color과 barmode를 통해 여러개의 그래프를 겹쳐서 그림.
Fig.update_yaxex() #y축을 우리가 원하게 바꿔줌

#Streamline
selectbox()
radio() #우리가 설정해놓은 여러 선택지를 선택할수있게 해준다
#Sidebar로 사이드바를 추가후 데코레이션을 사용해서 연속적으로 변하게 만들어줌
# 'https://github.com/blackary/st_pages'라는 라이브러리를 사용해서 우리가 원하는 선택지를 선택할시 main화면에 화면을 띄워줌 여기에 다양한 코트를 보는 예시가 존재
```

<br>

## 발표자료 
PPT
https://docs.google.com/presentation/d/18WeD68NM07TCBCJduix93Nn616BGuanRkyl0Tq3_CVM/edit?usp=drive_link

기획안
https://docs.google.com/document/d/1Apifd03AQ59bpAYK6zir9Hob5XiflluCkn1tDDfM2Gg/edit?usp=drive_link

대시보드
https://docs.google.com/presentation/d/17j37F8_-uDoz-gb4Tyewbb8Y7Ym_nYnIWsVp6ueEyNg/edit?usp=drive_link

<br>

## License
주소~ 서울 열린데이터광장 api
주소~ 국토교통부 실거래가 공개시스템 api
