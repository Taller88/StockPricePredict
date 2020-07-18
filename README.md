# StockPricePredict
Yahoo Finance 데이터 기반으로 회사들의 주가 예측

* Samsung Electronic
  - 활용 툴 
    goole Colaboaratory
  - 데이터 
    Yahoo finance에서 제공하는 데이터(data.csv) 
  - 알고리즘 
    LSTM 알고리즘 (Long Short Term Memory)
     * LSTM 알고리즘이란? 
      : LSTM은 RNN의 특별한 한 종류로 긴 의존기간을 필요로 하는 학습을 수행할 능력을 갖고 있다. 
        LSTM은 여러 분야의 문제를 굉장히 잘 해결했고 지금도 널리 사용되고 있다. 
          
        - RNN(Recurrent Neural Network)의 일종
          : RNN은 히든 노드가 방향을 가진 엣지로 연결돼 순환구조를 이루는 인공신경마의 한 종류 
          : 음성, 문자 등 순차적으로 등장하는 데이터 처리에 적합한 모델 
          : 활용함수(activation function) 은 비선형 함수인 하이퍼볼릭탄젠트(tanh) 
        - RNN의 장점 
           : 시퀀스 길이에 관계없이 인풋과 아웃풋을 받아들일 수 있는 네트워크 구조이기 때문에 
             필요에 따라 다양하고 유연하게 구조를 만들 수 있는다는 점이 RNN의 가장 큰 장점 
             
        - RNN의 단점 
           : RNN은 관련 정보와 그 정보를 사용하는 지점 사이 거리가 멀 경우 역전파시 그라디언트가 
             점차 줄어 학습능력이 크게 저하됨(Vanishing Gradient Probelm)
             
