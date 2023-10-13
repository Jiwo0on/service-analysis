# service-analysis
Google Analytics를 사용하여 교육 콘텐츠를 제공하는 사이트의 전환율 향상을 위한 프로젝트를 진행하였습니다. 

### 서비스 소개
<코사다마 커리큘럼 사이트>는 데이터 분석을 혼자 공부할 수 있는 커리큘럼을 제공하는 사이트입니다. 
파이썬 기초 문법, 머신러닝, 크롤링 등의 공부 방법 및 공부 자료들이 제공됩니다.
### 문제상황
매우 낮은 리텐션, 짧은 접속시간 -> 지속적인 학습이 이루어진다고 보기 어려움
### 목표
75% 스크롤, 30초 이상 머물렀을 때 학습이 완료된 것(=전환이 된 것으로) 설정하고 전환율 10% 상승을 목표로 분석을 진행함
### 분석 진행 방법
#### GA4를 활용한 사이트 분석 -> 전환 기회 찾기
- 퍼널분석: 이탈률이 가장 높은 구간
- 경로분석: 고객이 핵심 페이지, 단계 이후 어디로 가는지 -> 기대하던 곳인지 아닌지
- 이탈률 분석: 이탈하는 페이지 분석
- 페이진 전환: 전환율 높은 페이지, 낮은 페이지 비교

- sql 2-4 페이지에서 특히 높은 평균 사용시간?과 조회수가 가장 높았음. 해당 페이지는 
#### 가설 설정
1. 커리큘럼 페이지 중에서 외부 사이트로 연결되는 페이지들의 평균 활동 시간은 짧을 것이다.
2. 
3. 
#### A/B 테스트 설계
1. 외부 사이트로 연결되는 페이지들의 내용을 해당 페이지에서 볼 수 있도록 수정함
2. 
### 결과
커리큘럼맵을 제공하는 것을 차이가 없는 것으로 나타났다. 

### 해결방안
#### 경험
사용자가 생각하게 만들지 말 것. 사용이 쉽고 훌륭한 사용자 경험을 제고하는 사이트는 전환이 잘 됨 -> UX 단순화
#### 선택
의사결정 단순화 -> 커리큘럼맵을 제공하여 어떤 과정을 공부하면 좋을지 바로 알 수 있게 함



### 한계점 및 아쉬운점

### 추가 분석을 진행한다면
- 게이미피케이션 적용 -> 현재까지 학습이 몇% 완료되었는지 바로 확인할 수 있는 이미지 삽입 
인스타그램, 블로그 등 홍보를 다시 진행하여 충분한 사용자 유입이 되도록 할 예정 
- 특정 페이지(sql 2-4)에 접속하는 사람들 대상으로만 실험을 진행하였는데, 이를 보완하여 다수의 사람을에게 영향을 주는 변화

