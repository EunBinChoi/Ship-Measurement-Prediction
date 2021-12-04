1) TAPE A ~ F에 따라서는 구조를 알 수 있다. (0 or 1)
   -> pre processing으로 해결

2) 상기 1)에서 1인 애들을 예측한다.
   -> 예측할 때 공통적으로 숫자가 있는 y값이 있고, type별만 숫자가 있는 y값이 있다.
       있는데, 공통적으로 있는 애들은 전체 y값으로 학습한다. 
       type별로 있는 애들은 각 type별로 학습 (model_v3)

3) type별로 학습하기 위함 (model_v4)

-------------------------------------------------------------

type A: A1 ~ A8 (8개)
test dataset: A1, A2 (2개)
train dataset: A3 ~ A8
----------------------
type B: B9 ~ B38 (30개)
test dataset:  B9 ~ B15 (7개)
train dataset: B16 ~ B38
----------------------
type C: C39 ~ C45 (7개)
test dataset: C39, C40 (2개)
train dataset: C41 ~ C45
----------------------
type D: D46 ~ D52 (7개)
test dataset: D46, D47 (2개)
train dataset: D48 ~ D52
----------------------
type E: E53 ~ E71 (19개)
test dataset: E53 ~ E56 (4개)
train dataset: E57 ~ E71
----------------------
type F: F72 ~ F91 (20개)
test dataset: F72 ~ F75 (4개)
train dataset: F76 ~ F91

---------------------
총계
training data set: 70개
test data set: 21개