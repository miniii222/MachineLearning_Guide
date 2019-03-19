# MachineLearning_Guide
파이썬 머신러닝 완벽가이드 정리

처음부터 차근차근 다시 정리하자!!


# 1 파이썬 기반의 머신러닝과 생태계 이해 [Link](https://github.com/miniii222/MachineLearning_Guide/tree/master/Ch1_Understanding)
### numpy
- ndarray는 같은 타입의 값들만!

### pandas
- inplace=True의 return값은 None! -> inplace=True 후 새로우 변수에 할당되는 값은 None
- axis = 0 : row / axis = 1 : columns
- numpy [] 와 pandas dataframe []는 다름
- loc[] : 명칭 기반 인덱싱만 가능. 
- iloc[] : 위치 기반 인덱싱만 가능.
- 명칭 기반 인덱싱에서 슬라이싱을 하면 종료점을 포함한 위치까지 반환
- groupby후 agg할 때, 딕셔너리타입으로 칼럼별 다른 함수 지정 가능

# 2 사이킷런으로 시작하는 머신러닝
- GridSearchCV의 최적 성능을 나타내는 하이퍼파라미터로 학습해서 best_estimator_로 저장


# 3 평가

# 4 분류

# 5 회귀

# 6 차원 축소

# 7 군집화

# 8 텍스트 분석

# 9 추천 

- 정리 [link](https://github.com/miniii222/BOAZ_adv_project/blob/master/study/PYTHON_ML_GUIDE%20-%20RS.md)
