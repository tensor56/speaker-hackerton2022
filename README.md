# Speaker 팀
## 자유세션 - 인공신경망 기반 대구지역 미세먼지 농도 예측
Long-short term memory 와 N-BEATS를 이용한 대구지역 미세먼지 농도 예측

## 프로젝트에 대한 설명
온도, 기온, 태풍경로등의 기상환경 예측은 중요한 문제로서 그 중 미세먼지는 우리의 건강에 직접적인 영향을 미친다.
따라서 미세먼지를 예측하는 것은 우리의 건강을 지키는데 중요하게 작용할 것이다.

인공신경망을 이용하여 대구지역 미세먼지 농도를 예측해 보았다.

예측을 위해 사용한 인공신경망은 Long-short term memory, N-BEATS를 사용하였고 이를 비교해 보았다.

데이터는 기상청에서 제공받았으며, 2017.01.01 ~ 2021.12.31까지 사용하였다. 중간의 결측치는 linear interpolation을 사용하였다.

## 프로젝트에 활용된 기술
* Pytorch Forecasting 라이브러리 활용
* LSTM 인공지능 모델 사용
![img](img/lstm_cell.png)
출처: https://colah.github.io/posts/2015-08-Understanding-LSTMs/

* N-BEATS 인공지능 모델 사용
![img_1.png](img/nbeats_cell.png)
출처: https://arxiv.org/abs/1905.10437


## 시연영상
* [LSTM](https://youtu.be/XpSFPV5t8nw)
![LSTM](img/lstm.png)
* [N-BEATS](https://youtu.be/ZDSF0wV-I4k)
![NBEATS](img/nbeats.png)
