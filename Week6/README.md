# 6주차

## 6장. 생성모델 실습

1. DCGAN

- DCGAN은 기존의 GAN 구조를 모두 deep convolutional layer로 변경하였다는 특징이 있습니다.
- Convolutional layer와 batch normalization을 추가하여 모델 생성에 안정성을 더하였습니다. 심지어 discriminator 부분에서는 fully connected layer 조차 쓰지 않습니다!
- DCGAN의 학습은 latent vector간에 수학적 연산이 가능하다는 특징이 있습니다. 
- Paper: [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)

2. 실습코드

- 실습코드는 CelelA 유명인 얼굴 데이터를 이용하여 생성모델을 학습하였습니다.
- CelebA에는 유명인 1만명에 대해 약 20만장의 얼굴 이미지가 포함되어 있습니다. (약 1.34GB)
- Dataset link : https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
- 해당 링크의 google drive에서 데이터셋 다운로드 후 본인의 google drive에 저장하여 colab과 연동하면 되겠습니다.
- 해당 코드는 64x64의 이미지를 생성합니다. 여러분들은 모델을 변형하여 224x224의 이미지를 생성해보시길 바랍니다.