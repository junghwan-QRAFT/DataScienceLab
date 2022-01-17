### 문제 정의
최근 주식을 시작하게 되면서, Data Driven으로 주식을 고찰하면 높은 수익률을 얻을 수 있으리라는 생각을 가지게 되었다.
이미 퀀트 투자, 로보 어드바이저 등 금융 업계에 AI를 적용하려는 움직임이 많이 있는 바, 이를 바탕으로 실험해보고자 한다.
금융 시장은 개인의 투자 성향 등의 Micro Data와 증권사, 헤지펀드에서 산정하는 지수, 정책 등의 Macro Data에 대해 고찰이 필요한 고도로 복잡한 도메인이라는 생각이 들어 여러 금융 데이터를 통해 인사이트를 얻어보고자 한다.

## ** 삼성전자 주식 가격 예측 with ARIMA, Prophet
ARIMA, Facebook Prophet 등 시계열 데이터의 주기성, 계절성을 바탕으로 예측을 진행하는 모델에 대해서 실험해보고자 하였다.
### 인사이트
주식의 등락에 주기성이 존재하는 것은 사실이지만, 주기성만으로는 주식 가격을 예측하는데 한계가 있었다.
[ipynb 파일 바로보기 with Nbviewer](https://nbviewer.jupyter.org/github/jhbale11/DataScienceLab/blob/main/Dacon/%EC%82%BC%EC%84%B1%EC%A0%84%EC%9E%90%20%EC%A3%BC%EA%B0%80%20%EC%98%88%EC%B8%A1_ARIMA_PROPHET.ipynb)

## ** 삼성전자 주식 가격 예측 with RNN, LSTM
