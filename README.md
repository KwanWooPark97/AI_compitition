Ai 대회 첫 참가

사진 데이터를 기반으로 continual learning을 진행하는 대회

내가 찾은 방법은

1.Resnet
2.EWC
3.Vision Transformer 

3가지 였는데 성능 자체는 3번이 제일 좋았다 하지만 Transformer 특성 상 데이터가 많아야 한다. 데이터가 label당 100개 밖에 없어서 굉장히 적었음...
EWC는 continual learning에서 가장 보편적으로 사용하는 기법으로 보임 대신 계산 속도가 많이 느렸고 코드 적용하기 어려웠음 무난한 성능을 보여줌
Resnet은 제일 무난한 image classifications network이므로 사용해서 확인해봄. 첫번째 학습은 성능이 좋지만 학습이 넘어갈수록 성능이 바닥을 침
