# 2020 K-water 대국민 빅데이터 공모전 참여 결과물

## 쉽고 빠른 가뭄 정보 앱
5인 제작

## 목적
지역별 지하수 관측소 수위 정보를 제공하여 사용자가 손쉽고 빠르게 정보에 대한 접근을 가능하게 하고 미리 가뭄 대비를 할 수 있게끔 한다.

## 주요 내용
우리나라 지도에 지하수 관측소 위치별 마커를 부여함. <br/>
	* 마커 클릭 시 관측소별 분석 결과 페이지로 이동 <br/>
지하수 수위를 한 달간 지하수 관측 결과와 월평균 수위 결과를 그래프를 사용하여 한 눈에 볼 수 있도록 함.  <br/>
	* 발생 기준을 보여 가뭄에 대한 정확한 정보를 전달함. <br/>
	* 발생 시 권장되는 행동 요령을 제시함. <br/>
  
## 수행 과정
0주차 : DB, 설계 및 개발, design으로 개인의 경험에 맞추어 분담 진행. <br/>
1주차 : csv파일을 전처리, 네이버 맵 API를 통해 맵 구현. <br/>
2주차 : firebase서버와 android studio를 실시간 DB연동, 각 관측소 위치에 마커를 찍음. <br/>
3,4주차 : 관측결과에 따른 가뭄 측정의 기준과 가뭄 발생 시 민간에서 할 수 있는 행동요령을 추가.  <br/>
5주차 : 로딩페이지, 아이콘 구현. 색, 글씨체 수정, 가독성이 좋은 그래프를 사용. <br/>


![image](https://user-images.githubusercontent.com/64747722/121365495-a913c800-c973-11eb-9c22-56963d37d3b0.png)![image](https://user-images.githubusercontent.com/64747722/121365556-b7fa7a80-c973-11eb-8a80-b1116d05c568.png)![image](https://user-images.githubusercontent.com/64747722/121365601-c052b580-c973-11eb-9527-fbb866850294.png)![image](https://user-images.githubusercontent.com/64747722/121365629-c6e12d00-c973-11eb-8fcf-fe61280ece04.png)![image](https://user-images.githubusercontent.com/64747722/121365655-cc3e7780-c973-11eb-9cdc-14088a731b03.png)<br/>
- 어플 아이콘 - 로딩 화면 - 시작 후 첫 화면 - 마커 클릭시 화면 - 가뭄 발생 시 행동 요령

## 데이터 출처
 국가가뭄정보포털 : http://www.drought.go.kr <br/>
 환경빅데이터플랫폼 > 지하수 관측소별 가뭄분석 정보 : https://www.bigdata-environment.kr


  




