# 김승주 
```
데이터를 가지고 최대의 성과를 만들기 위해 공부하고 노력하는 개발자, 김승주입니다.
```

## Intro
* Name : 김승주
* Birth : 1990.10.19
* Address : 천안시 서북구 공원로
* E-mail : zmffotm57@gmail.com
* activity : 코리아IT아카데미, 빅데이터를 활용한 AI챗봇&광학기술 개발자 과정(6개월)
  - 내용 
        
        DB
        - 데이터베이스의 정의 및 기본 개념
        - 데이터 모델링
        - 데이터 정규화
        - DML, DDL, TCL, DCL
        - JOIN과 서브쿼리 활용

        Python
        - 파이썬 기초 문법
        - 제어문 학습
        - Pandas 데이터 구조 학습
        - 데이터 정제
        - requests, beautifulsoup, selenium을 활용한 웹크롤링
        - Numpy 다차원 배열 이해
        - 데이터 시각화

        DJango
        - MVT 패턴 학습
        - ORM 활용
        - RESTAPI 개념 학습
        - Template과 디렉터리 학습

        Machine Learning
        - 머신러닝의 개념
        - 회귀/분류
        - 지도학습/비지도학습
        - 모델 평가 지표
        - sklearn을 활용한 머신러닝 데이터 분석
        - Tensorflow, keras, PyTorch 사용 방법 숙지
        - 인공 신경망 구축
        - 챗봇 모델 개발
        - CNN 기반 문자 인식 모델 개발
            
## Projects
#### 서울시 미세먼지 실시간 예측 프로젝트
> 유형 : 팀프로젝트
> 
> 내용 : 서울, 인천, 경기의 기상관측, 대기오염 데이터를 활용해서 24시간 뒤 서울시 종로구의 미세먼지 농도를 예측하는 모델 생성
> 
> 역할
>- 스킬 : Python
>
>- 라이브러리 : Pandas, Numpy, Scikit-Learn, Tensorflow, Matplotlib, Seaborn
>
> 1) API 데이터 수집
> 
> - 기상자료개방포털 OPEN-API 데이터 활용
> - 경기도, 서울, 인천 지역별 데이터 수집
> 
> 2) 데이터 분석
> 
> - 결측치 처리 : drop할 컬럼, 0으로 대체할 컬럼, 앞 뒤 값의 평균으로 대체할 컬럼 선정 및 처리
> - datetime 컬럼이 없는 데이터 확인 -> 바로 뒤의 데이터와 동일한 값으로 처리 
> - 다양한 기상현상(안개, 천둥, 황사 등)을 수치화한 컬럼 원핫인코딩 처리
> 
> 3) 딥러닝 모델 학습
> 
> - 회귀 모델
>   - 피처 선정하기 위해 기존 피처, PCA, Randomforest의 feature_importance 총 3가지 방법으로 RMSE 확인 후 가장 낮은 수치가 나온 feature_importance로 결정 (2,530개의 컬럼 중 1,577개 제거)
>   - CNN 모델 결정
>     - 많은 피처에 대한 특징을 추출할 수 있는 CNN 선정
>     - 베이스라인 모델 선정 후 여러 파라미터를 수정하며 모델 성능 확인 (RMSE 기준)
>       - epoch, maxpool1D, strides, dropout, kernel_size, learning_rate, batch_size 수정
>       - MinMaxScale, RobustScale 사용
>        
> 프로젝트 관련 소스 : https://github.com/seoyoonjoannechang/SUM_Project

## Blog
> 6개월동안의 수업 관련 내용 정리 및 개인 공부 공간
> 
> https://blog.naver.com/dirn57
