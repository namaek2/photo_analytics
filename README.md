# photo_analytics
먼저, Pytorch에서 훈련된 weights를 가져왔다. 
Weight를 처음부터 훈련을 시키면 너무 시간이 오래걸린다는 이유에서이다. 
그리고 가져온 weight로 모델을 구성했는데, 이때 기존 모델의 fully connected layer 층을 없애고, 우리가 원하는 값들의 fully connected layer로 재구성하였다. 
현재 모델은 미완성 상태이다.
