# Social Network Analysis

바이럴 마케팅에 활용할 소셜 인플루언서 선별 모형

https://www.kaggle.com/yelp-dataset/yelp-dataset

## 목적
  - 옐프는 단순 리뷰사이트가 아닌 유저들끼리 친구맺기 기능이 있는 소셜네트워크 시스템도 제공한다. 옐프가 제공하는 소셜네트워크 데이터를 통해 바이럴 마케팅에 활용할 영향력이 높은 소셜 인플루언서들을 선별 한다.

## 데이터
yelp_academic_dataset_user.json 데이터에서 아래 두 칼럼을 사용하여 소셜 네트워크 데이터를 구성한다.
  - user_id: 사용자 id
  - friends: 사용자 친구 목록

## 소셜 네트워크 분석
### [Social Network Analysis](https://github.com/hojisu/network_analysis/blob/master/social_network_analysis.ipynb)
  - 소셜 네트워크 상에서 유저의 중요성을 측정하는 모형들을 통해 소셜 인플루언서들을 선별한다.
  - 각 모형에서 선별된 인플루언서들을 통해 네트워크 상에서 정보가 퍼지는 속도를 시뮬레이션하여 선별 모형의 성능을 평가한다.
