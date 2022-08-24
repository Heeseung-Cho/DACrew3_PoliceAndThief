# 8주차

## 8장. 생성모델 실습 2

1. Baseline

- Baseline code는 저번 시간에 배운 LSGAN입니다. LSGAN은 기존의 loss를 least square를 이용하여 학습을 하게 됩니다.
- 실습 코드는 매우 간단합니다! Loss를 MSELoss로 바꿔주기만 하면 됩니다.
- 또한, 224x224의 이미지를 만들기 위해 generator와 discriminator를 어느정도 조절하였습니다. 

2. 실습데이터

- 실습데이터는 Dacon에서 제공하는 딥페이크 변조 영상 탐지 AI 경진대회를 이용하였습니다.
- 해당 데이터의 Test data(약 0.6G)를 기반으로 가짜 데이터를 생성해 보시길 바랍니다.
- Dataset link : https://dacon.io/competitions/official/235655/data
