# 🔎 Data_Analyst_Note



- 비즈니스 및 사용자의 대한 이해가 필요하다.

- 문제 정의를 명확하게 해야한다.
  - 기업의 상황으로써 타당한지 생각한다.
  - 어떤 점이 매출을 저하시키는지, 어떤점을 보완 및 강화를 해야할지 생각한다.
- 기술적 정교함과 난이도에만 매몰되지 않아야 한다.
    - “그래서 돈이 되는가?” 가 제일 중요한 것이다.
    - "문제 해결을 위한 일인가?"로 접근한다.
    - 기술자가 모델의 성능과 기술에만 심취하는 것을 피하도록 한다.
    - 세상에 모든 기술들은 실제로 활용되어야 의미가 있다.

- 데이터에 대한 이해를 한다.
  - 데이터를 통해 파악해야할 지표, 요인들에 어떤것이 있는지 생각해본다.

- 가설의 정립과 통계적으로 타당성을 검증한다.
  - 세부 문제 사항에 대해 가설을 세운다.
  - 통계를 통한 현상을 파악한다.
  - 독립성 검정, 상관분석, 요인분석
  - 가설을 리스트업하고 어떻게 테스트할지 생각해본다.

- 데이터 분석은 최적의 시각화를 찾기 위한 여정이다.

- 서면, 구두로 설명이 가능해야 한다.

## 분석 보고서에 넣을 내용
- 프로젝트의 개요
  - 비즈니스의 의미를 부여한다.
  - 왜 이런 프로젝트를 기획하고 있는가?
  - 이 프로젝트는 어떤 문제를 해결할 수 있는가? 

- 프로젝트의 진행과정을 단계별로 작성한다.

- 시장의 인식 변화에 대한 내용
  - 키워드 분석을 사용하는 것도 좋은 방법이다.

- 데이터셋의 출처, 크기, 특성에 대한 내용

- 분석기법과 알고리즘 모델 방법론등에 대한 상세한 설명
  - 데이터 분석에서 머신러닝 모델은 대부분 Decision tree / SUM를 쓴다.

- 결론과 인사이트
  - 프로젝트의 비즈니스 측면에서 가치를 설명 할 수 있어야 한다.
    - 에러 또는 리스크를 줄일 수 있다.
    - 사용자의 편의성을 높힐 수 있다.
    - 매출을 늘릴 수 있다.
    - 시간 및 비용을 아 수 있다.
  - 시각화 및 대시보드를 활용한다.(Tableau, BigQuery)
  - 문제 또는 그 원인을 해결할 수 있는 액션 또는 마케팅 전략을 찾는다.
    - 분석결과에 따라 상황적으로 실현가능하고 합리적이어야 한다.
  - 뻔한 결과, 당연한 내용을 최종적인 결론으로 가져오는것을 피한다.
  - 


- 필요에 따라서 분석보고서의 회고와 발전가능성에 대해서 작성한다.
  - 프로젝트에서 아쉬웠던 점, 부족했던 점, 한계점 등 정리하는 것도 좋다.
  - 더 나은 조건에서 진행한다면 개선하고 싶은 점을 정리한다.

- 다른 레퍼런스를 가져오는 것은 정말 좋다.

## 시각화

### 1. 시각화에서 강조하고 싶은 부분을 잘 표현했는지 고려해야한다.



### 2. 옳지 않은 시각화란?
  - 그래프의 색상 선택을 고려하지 않은 경우
    - 많은 색을 사용하는 것은 눈에 피로감을 줄수있다.
    - 연한색을 사용하는 것이 좋다.
      - 보는 사람이 색약이 있는경우 단색의 차이를 구분하기 어렵다.
      - 단색은 시각화에서 중요하거나 강조하고자 하는 부분에만 사용한다.
    - 그래프에서 비슷한 계열의 색을 사용할경우 확인하는 것이 어려워질수있다.
    
  - 전달하고자 하는 메세지를 담지 않거나 파악하기 힘든 시각화이다.
  
  - 전달하고자 하는 메세지가 정확하지 않거나 왜곡되어진 시각화이다.
  
  
#### 📌 예시
- 미미한 증가를 확대해서 보여주는 경우(y축의 시작이 0이 아닌 경우)
- 기울어진 파이차트의 경우 가까운 부분은 크게보이고 멀리있는 부분은 작게 보이는 경우.
- Title, y축, x축이 무엇을 의미하는지 정확하지 않은 경우.
- list of values의 값이 그래프를 가려서 확인에 어려운 경우.



### 3. 옳은 시각화란?
  - x축, y축, title을 통해 전달하고자 하는 메세지가 명확한 시각화이다.
  - 정보가 정확해야하고 왜곡되어 보이지 않아야 한다.
  - 중요한 부분이 색으로 잘 강조되고, 나머지 부분은 최소화하는 시각화이다.
  - 메세지를 파악하기 쉬운 시각화이다.
  
  
#### 📌 예시
- font size가 적절하게 되어있어서 파악하기 쉬워야 한다.
- 강조하고자 하는 그래프에 색을 명확하게 사용하며 눈이 불편하지 않아야 한다.
- 정보를 파악하기 쉬운 위치에 그래프의 list of values값을 존재시킨다.


  
## 워드 클라우드 (Word cluod)
- 소셜네트워크 분석기법으로 키워드의 크기만을 고려하는 분석보다는 거리까지도 고려하는 시각화를 선택하는것이 좋다.

## 파이차트 (Pie chart)
- 3~4개 이상의 값들을 비교해야 한다면 지양 하는것이 좋다.
  - Pie Chart는 여러값들의 비율을 파악하기 힘들다.
  - Bar plot을 사용하는 것이 좋다.
  
## 막대그래프(Bar plot)
- 각 범주(category)의 수치 값을 비교할때 적합하다.
-  Multiple Bar Plot의 경우는 카테고리 그룹별로 값를 비교할 때 사용한다.
-  Stacked Bar Plot은 여러개의 그룹의 값을 쌓아서 표현한다.
-  Overlapped Bar Plot은 쌓아서 비교하기 어려울 때 겹쳐서 표현하는 방법이다.
-  Grouped Bar Plot은 그룹별 카테고리 bar를 모아서 배치하는 방법이다.
