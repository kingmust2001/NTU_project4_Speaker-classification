# NTU_project4_Speaker-classification

## 專案介紹
Predict speaker class from given speech.

![image](https://user-images.githubusercontent.com/77257138/150798318-50443815-231d-420a-accb-8c64882ac480.png)

## 軟硬體配置
* CPU: Intel(R) Xeon(R) (6-cores)
* GPU: Tesla K80 (11.44GB)
* OS： Window10
* Pytorch: 1.10.0
* keras: 2.7.0
* tensorflow: 2.7.0
* Memory: 12.69GB
## 資料來源
VoxCeleb - A large scale audio-visual dataset of human speech

link: https://www.robots.ox.ac.uk/~vgg/data/voxceleb/
## 資料基本資訊
* Training: 69438 processed audio features with labels.
* Testing: 6000 processed audio features without labels.
* Label: 600 classes in total, each class represents a speaker.

## 前處理
Acoustic Features(聲學特徵) - MFCCs (Mel Frequency Cepstral Coefficients)

![image](https://user-images.githubusercontent.com/77257138/148779813-09c935f8-efd3-458b-bfe1-73d5b00c7ee0.png)
![image](https://user-images.githubusercontent.com/77257138/148779831-68fd8f84-2ad0-4ab4-b0b6-d2afae49705d.png)

## 模型

## Metrics
CROSSENTROPYLOSS

![image](https://user-images.githubusercontent.com/77257138/148780873-c5a60568-bc3b-4494-87c3-fe4bd144974a.png)

Note:This criterion combines LogSoftmax and NLLLoss in one single class.
## 成果

## Reference
https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html

## other

![image](https://user-images.githubusercontent.com/77257138/150798921-4708a44b-4894-4d45-8f88-12e74d9e3cd6.png)

