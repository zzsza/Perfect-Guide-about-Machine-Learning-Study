# Perfect-Guide-about-Machine-Learning-Study
- 파이썬 머신러닝 완벽 가이드 쏘카 데이터그룹 사내 스터디 보완 자료

## 책에 대한 설명
- (작가 서문 참고)
- 다양한 실전 예제를 직접 구현해 보면서 머신러닝을 체득할 수 있도록 만듬
- 최대한 수학적 사용은 배제하면서 코드 작성과 예제를 통해 핵심 개념을 이해할 수 있도록 함
- 어느정도 머신러닝에 경험이 있는 독자들을 대상으로 집필

## 스터디 방식
- 매주 월요일마다 스터디(2시간)
	- 미리 준비할 필요 없이, 스터디 시간에 책을 읽음
	- 타이머 시간 설정을 한 후 각자 읽어봄(Default : 15분)
	- 코드도 눈으로 보고 넘김
- 각자 읽은 부분 중
	- 중요하게 생각하는 것
	- 나에게 특히 영감을 준 부분
	- 의문점이 드는 것 등을 공유
- 분량이 너무 많은 경우 타이머 시작하기 전에 섹션을 나눈 후 읽고 담당 섹션에 대해 이야기
- XGBoost, LightGBM의 경우 논문에 대해 읽어보기
	- 우리가 속한 분야는 새로운 아이디어가 계속 나오는 분야
	- 논문을 접하는 것이 중요하기 때문에, 논문 읽는 것에 대한 습관을 위해 진행 (모두 이해하지 못해도 괜찮음)
	- [XGBoost Paper](https://arxiv.org/abs/1603.02754)
	- [LightGBM Paper](https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree.pdf)
	- 논문 이해가 잘 안되는 경우 부가 자료도 함께 읽어보며 학습
        - (아이디어) 논문을 바로 읽으면 어려울 수 있으므로, API Document를 본 후 진행하는 방법
        - 이 경우, 공식 Document를 (일부분만) 번역해서 Socar Repo에 공유하면 어떨까? => 스터디 + 대외적 홍보 효과
        - [XGBoost Document](https://xgboost.readthedocs.io/en/latest/index.html)
        - [LightGBM Document](https://lightgbm.readthedocs.io/en/latest/)

<details><summary>XGBoost, LightGBM 부가 자료</summary>
<p>
	
- [XGBoost 관련 글](https://brunch.co.kr/@snobberys/137)
- [LightGBM 번역 글](https://aldente0630.github.io/data-science/2018/06/29/highly-efficient-gbdt.html)
- [XGBoost, LightGBM 파라미터 설명 글](https://sites.google.com/view/lauraepp/parameters)
- [Introduction to Boosted Trees PPT](https://homes.cs.washington.edu/~tqchen/pdf/BoostedTree.pdf?fbclid=IwAR0gGntURg4U24l6Fit-DLpVNBb_BtgMjzlSg3NYdb8jI44JLHLH-0Zluis)
- [CatBoost vs LightGBM vs XGBoost 비교 글](https://towardsdatascience.com/catboost-vs-light-gbm-vs-xgboost-5f93620723db)
	
</p>
</details> 

- 코드 구현
	- 2가지 방식으로 진행할 예정 
	- 1) 2명이 하나의 노트북을 두고 Pair Programming
		- (의견 받습니다. 2명 팀으로 각자 노트북에서 진행?) 
	- 2) 캐글 커널 필사 (따라 치기) => 이것도 짝꿍은 있되, 각자 노트북으로 진행

## 책의 목차
- 스터디에서 모두 진행하진 않을 예정
- 1) 파이썬 기반의 머신러닝과 생태계 이해 (86p)
	- Numpy, Pandas 
- 2) 사이킷런으로 시작하는 머신러닝 (55p)
	- sklearn Estimator, Model Selection, 데이터 전처리 
- 3) 평가 (34p)
	- Accuracy, Precision, Recall, Confusion Matrix, F1 Score, ROC Curve, AUC 
- 4) 분류 (105p)
	- Decision Tree, Ensemble, Random Forest, Gradient Boosting Machine, XGBoost, LightGBM, Under Sampling/Over Sampling, Stacking 
- 5) 회귀 (85p)
	- Linear Regression, Lidge, Rasso, ElasticNet, Logistic Regression 
- 6) 차원 축소 (30p)
	- PCA, LDA, SVD, NMF 
- 7) 군집화 (54p)
	- K-means, Cluster Evaluation, Mean Shift, GMM, DBSCAN 
- 여기까지 449p
- 8) 텍스트 분석 (94p)
- 9) 추천 시스템 (63p)
	- 8), 9)는 다루지 않을 예정 


## 스터디 규칙
- 함께 자라기 : 동료가 성장하면 저도 성장하고, 업무 퀄리티도 좋아집니다
- 모르는 내용에 대해 서로 알려주기 : 모두 잘 알수는 없어요. 내가 모르는 내용을 다른 분이 알 수 있어요. 돕고 살아요
- 바로 물어보기 : 토론식 스터디라 바로 물어봐도 괜찮아요


### Repo 사용 방법
- Git clone

	```
	git clone https://github.com/zzsza/Perfect-Guide-about-Machine-Learning-Study.git
	```

- Repo를 최신화하고 싶은 경우

	```
	git pull
	```
	
### 스터디 기록 및 회고
- 19.03.18
	- 1장. 파이썬 기반의 머신러닝과 생태계 이해(~p.86) 읽음
	- Kaggle 실습 진행
	- 저녁 식사를 미리 고민할 것(맥도날드가 너무 늦게 옴)
	- 사람들의 책 읽는 속도에 대한 감을 알게 됨 => Default Minute을 15분이 아닌 25분으로 조정
	- 스터디에 조금 늦은 사람과 기존에 참여한 사람과 시간 차이가 벌어짐
	- 어디까지 진행할지 언급
	- 어쩌다 보니 스터디 3시간 진행

- 19.03.25
	- 스쿨푸드 먹음
	- 2장 전체 읽음
	- sklearn
	- train_test_split
	- Estimator - fit(), predict()
	- cross_val_score() 
	- KFold, StraritifiedKFold
	- GridSearch()
	- Ont Hot Encoding / Label Encoding Scaler
	- 피드백! 
		- 실습 형태 : 3명 중 2명이 **개인**을 선호
		- 복습 자료 : 3명 중 2명이 **복습 자료는 부담스럽다**
		
- 19.04.01
	- 피자스쿨 먹음
	- Metric에 대한 이해
	- 각 Metric을 왜 사용하는지 이해하기 
- 19.04.08
	- 햄버거 먹음
	- Decision Tree
	- 정리하며 읽기
	- sklearn tree 구현체 파악해보기
	- Regression 문제일 땐 어떻게 information gain을 측정할까? => Standard Deviation : [참고 자료](https://www.saedsayad.com/decision_tree_reg.htm)
- 19.04.15
	- 제가 아파서 스터디 참여 못했 ^_ㅠ
	- 256쪽 분류 실습 전까지 읽음
	- 디테일한 내용에 대해 논의 했지만 답은 못 찾은? 경우가 있었던 것 같음
- 19.04.22
	- 타코 먹음
	- XGBoost 논문 리뷰
	- 머리가 매우 아프지만, 저희가 있는 도메인은 논문을 접하는 것이 매우 중요하기 때문에! 계속 노력해보는 것이 중요하다고 생각
	- 수학에 대한 것은 보충하며 진행하면 될 것이라 생각
- 19.04.29
	- 버거킹 먹음 
	- LightGBM
	- Imbalanced Data 처리하는 방법
- 19.05.13
	- 김밥 먹음 
	- 5장 회귀 부분 다 읽음 
- 19.05.20
	- 치킨 먹음 
	- 5장 회귀 부분 실습 진행	

	
### Reference
- 김창준님의 [스터디 모임 방법 몇 가지](http://agile.egloos.com/5830026)
- [파이썬 머신러닝 완벽가이드 예제 코드 Github](https://github.com/wikibook/ml-definitive-guide)
