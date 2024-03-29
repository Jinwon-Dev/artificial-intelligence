# artificial-intelligence
인공지능 세미나를 진행하면서 공부한 내용을 기록합니다.

파이썬을 이용해 작성하며, 머신러닝과 딥러닝에 관해 매주 기록합니다.

-----
실습 해본 코드는 [Github](https://github.com/Jinwon-Dev/artificial-intelligence)에 저장하며, 정리한 내용은 [Notion](https://jinwonyoon.notion.site/Artificial-Intelligence-b01648e7ae1d4d1b97b523fe73c480d9)에 기록합니다.

- Chapter 1 : [나의 첫 머신러닝](https://jinwonyoon.notion.site/Chapter-1-0ee0eb675a9940ea84fba15006111299)
  - **인공지능과 머신러닝, 딥러닝**의 개념을 이해합니다.
  - **k-최근접 이웃 알고리즘**을 사용해봅니다.
    - `KNeighborsClassifier()` 클래스를 이용하여 k-최근접 이웃 분류 모델을 만들어 봅니다.

- Chapter 2 : [데이터 다루기](https://jinwonyoon.notion.site/Chapter-2-a676d519ae7846af850784f81947d75d)
  - **지도 학습과 비지도 학습**에 대해 알아봅니다.
  - 모델을 훈련시키는 **훈련 세트**와 모델을 평가하는 **테스트 세트**로 나누어 학습합니다.
    - `numpy` 배열 라이브러리를 사용하여 고차원을 배열을 만듭니다.
  - **데이터 전처리**에 대해 알아보고, **표준 점수**를 이해합니다.

- Chapter 3 : [회귀 알고리즘과 모델 규제](https://jinwonyoon.notion.site/Chapter-3-d1d6c7093ca54751a892c0132d5c57d2)
  - **회귀**의 개념과 **k-최근접 이웃 회귀**에 대해 알아봅니다.
    - **결정 계수**와 **과대적합, 과소적합**을 이해합니다.
    - `KNeighborsRegressor` 클래스를 이용하여 k-최근접 이웃 회귀 모델을 만들어 봅니다.
  - **선형 회귀**와 **다항 회귀**에 대해 알아봅니다.
    - `LinearRegression` 클래스를 이용해 선형 회귀 모델을 구현해 봅니다.
  - **다중 회귀**와 **규제**, **특성 공학**에 대해 알아봅니다.
    - 데이터 분석 라이브러리인 `pandas` 를 이해합니다.
    - 규제가 있는 회귀 알고리즘인 **릿지**와 **라쏘**에 대해 알아봅니다.

- Chapter 4 : [다양한 분류 알고리즘](https://jinwonyoon.notion.site/Chapter-4-c979e7fea39c45e794ead4422edb6e7e)
  - **로지스틱 회귀 알고리즘**과 다중 분류에 대해 알아봅니다.
    - `LogisticRegression` 클래스를 이용하여 로지스틱 회귀를 구현해 봅니다.
  - **확률적 경사 하강법**과 **손실 함수**, **에포크**에 대해 알아봅니다.
    - `SGDClassifier` 를 이용해 확률적 경사 하강법을 사용한 분류 모델을 구현해 봅니다.  

- Chapter 5 : [트리 알고리즘](https://jinwonyoon.notion.site/Chapter-5-e92d2cf2c6ff45de86bea6757c00e1bc)
  - 성능이 좋고 이해하기 쉬운 **결정 트리 알고리즘**에 대해 알아봅니다.
    - `DecisionTreeClassifier` 클래스를 이용하여 결정 트리 분류 알고리즘을 구현해 봅니다.
    - **불순도**, **정보 이득**과 **특성 중요도**에 대해 알아봅니다.
  - 최적의 모델을 위한 하이퍼파라미터를 탐색해 봅니다.
    - **교차 검증**, **그리드 서치**와 **랜덤 서치**에 대해 알아봅니다.
  - 성능을 높이기 위해 여러 개의 모델을 훈련하는 **앙상블 학습**에 대해 알아봅니다.
    - `RandomForestClassifier` 클래스를 이용하여 **랜덤 포레스트**를 구현해 봅니다.

- Chapter 6 : [비지도 학습](https://jinwonyoon.notion.site/Chapter-6-6b4bfb0be90e48fc877fd050e54c77e4)
  - 타깃이 없을 때 사용하는 머신러닝 알고리즘인 **비지도 학습**에 대해 알아봅니다.
    - 대표적인 비지도 학습 작업인 **군집**에 대해 알아봅니다.
  - `KMeans` 클래스를 이용하여 **k-평균 알고리즘**을 구현해 봅니다.
    - **엘보우 방법**에 대해 알아봅니다.
  - 비지도 학습의 한 종류인 **차원 축소**에 대해 알아봅니다.
    - `PCA` 클래스를 사용하여 **주성분 분석 알고리즘**을 구현해 봅니다.

- Chapter 7 : [딥러닝을 시작합니다]

- Chapter 8 : [이미지를 위한 인공 신경망]

- Chatper 9 : [텍스트를 위한 인공 신경망]