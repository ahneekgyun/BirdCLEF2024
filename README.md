# BirdCLEF2024

Competition Link
https://www.kaggle.com/competitions/birdclef-2024

Colab 환경에서 구현  
Task : 음성 데이터를 받아 여러가지 새의 종류를 분류  
> Method  
> : Spectrogram 변환 후 time, frequency masking을 사용한 augmentation.  
> : ResNet18을 사용하여 Spectrogram을 학습시킴  
