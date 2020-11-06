# Reddit-data-analysis

### Reddit Data를 활용해 기본적인 분석 작업을 진행해본다.


## 분석 방법론

### 1) TF-IDF
- TF(Term Frequency): 특정 단어가 문서 내에서 얼마나 자주 등장하는지를 나타내는 값으로 해당 값이 높아지면 높아질수록 문서 내에서 중요하다고 생각할 수 있다.   
하지만 하나의 문서에서 많이 나오는 것이 아니라 다른 문서에도 자주 등장한다면 단어의 중요도는 낮아진다. 
- IDF(document frequency): 문서의 빈도의 역수값을 의미한다.   
- TF-IDF: TF와 IDF를 곱한 값으로 점수가 높은 단어일수록 다른 문서에는 많지 않고 해당 문서에서만 자주 등장하는 단어가 된다. [1]


### 2) Topic Modeling
1) LDA
2) LSA



## REFERENCE
[1] https://nesoy.github.io/articles/2017-11/tf-idf
