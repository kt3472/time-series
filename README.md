# Time-Series Data & Predictions

## 1. Overview

* Predicions of Time-Series data with Machine Learning Models


## 2. Data Analysis & Predictions

* [암호화폐 가격 예측 모델링](https://github.com/kt3472/time-series/tree/master/cryptocurrency_prediction)

  + Data Set : 2018년 ~ 2019년 Bitcoin, Ethereum의 일자별 종가 데이터(출처 : coinmarketcap.com)
  + Environment : python 3.6 / tensorflow 1.3.0, pandas, numpy, matplotlib
  + Models : LTSM, MonteCarlo simulation
  
* [상장기업 신문기사의 감성분석을 통한 주가 예측 모델링](https://github.com/kt3472/time-series/tree/master/sentiment_analysis)

  + Data Set : 2019년 10월 ~ 2020년 3월 상장기업 관련 신문기사/일자별 종가 데이터()  
  + Environment : python 3.6 / nltk, googletrans, tensorflow, beautifulsoup, pandas, numpy, matplotlib
  + Process : 언론기사 수집(Naver) -> 영어로 번역(GoogleTrans) -> 긍정/부정(NLTK) 확률 추출 및 입력변수로 사용 
  + Models : CNN
 
* [Naver Trends 예측 모델링(트렌드단어:"국세청")](https://github.com/kt3472/time-series/tree/master/naver_trends_prediction)

  + Data Set : 2016년 1월 ~ 2020년 2월 월간 "국세청" 단어의 네이버 검색 트랜드 데이터(출처 : https://trends.google.co.kr/)
  + Environment : python 3.6 / statemodels, pandas, numpy, matplotlib
  + Models : SARIMAX

* [Google Trends 예측 모델링(트렌드단어:"Virus")](https://github.com/kt3472/time-series/tree/master/google_trends_prediction)

  + Data Set : 2004년 1월 ~ 2020년 1월 월간 "Virus" 단어의 구글 검색 트랜드 데이터(출처 : https://trends.google.co.kr/)
  + Environment : python 3.6 / statemodels, scipy, pandas, numpy, matplotlib
  + Models : ARIMA

* [국내 Covid-19 데이터 분석](https://github.com/kt3472/time-series/tree/master/covid19_south_korea)

  + Data Set : 2020년 2월 ~ 일별 국내 covid-19 현황 데이터(출처 : https://www.kaggle.com/kimjihoo/coronavirusdataset)  
  + Environment : python 3.6 / plotly, pandas, numpy, matplotlib, sklearn, statsmodels
  + models : FaceBook Prophet, SVM, Linear Regression, LSTM


## 3. References

* https://github.com/mborysiak/Time-Series-Forecasting-with-ARIMA-and-LSTM
* https://github.com/huseinzol05/Stock-Prediction-Models
* https://github.com/gxercavins/time-series
* https://somjang.tistory.com/
* https://www.kaggle.com/ginajiyoungsong/prediction-by-prophet-mlp-lstm-etc-eda-analysis



