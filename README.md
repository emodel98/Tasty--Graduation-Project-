# Tasty-Graduation-Project


콘텐츠 기반 필터링과 word2vec 을 활용한 감성키워드기반 맛집추천서비스(종합설계프로젝트, 2021.03 ~ 2021.06)

- 스킬: Python, SQL / Recommender systems, Contents Based Filtering, Word2Vec, K-means Clustering, Weighted-Item2Vec
- 성과:웹앱 배포 2주뒤 유저 535명 달성, 추천결과 만족도 4점이상 93%달성
- 역할: 2가지 추천 알고리즘 개발, Contents Based Filtering research, Mysql 이용 데이터 분석



**주요 알고리즘**
1. 감성 키워드 유사도 기반 가게추천(rmood, pmood)
  - 대표 키워드 선정
  - 키워드 별(rmood, pmood) 유사 키워드 선정
  - 입력받은 감성 키워드와 가게의 감성 키워드 유사도 측정(코사인 유사도)
2. Weighted-Item2Vec(특허출원)
  - 가게 속성별 벡터화
  - 두 가게 간 속성별 유사도 측정
  - 두 가게 간 가중합 유사도 측정 -> 두 가게의 최종 유사도
