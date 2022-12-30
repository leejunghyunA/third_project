# 📊 발표주제 및 자료
### 유방암 임파선 전이 예측 모델 구현
[![발표자료 보러가기](https://user-images.githubusercontent.com/70292353/210043845-cd3d2fed-fec1-4d35-9be6-38a0a7f6f48f.png "발표자료 보러가기")](https://github.com/leejunghyunA/third_project/blob/6e2aae8208cc583d44d7d4241a169aaa7b5c44a3/2.%20%EA%B2%B0%EA%B3%BC%20PPT/%EC%9C%A0%EB%B0%A9%EC%95%94%20%EC%9E%84%ED%8C%8C%EC%84%A0%20%EC%A0%84%EC%9D%B4%20%EC%98%88%EC%B8%A1%20%EB%AA%A8%EB%8D%B8%20%EA%B5%AC%ED%98%84.pdf)<br/>


# 👩‍👩‍👧‍👦 팀원 소개

| 팀원 | 업무 | 깃허브 주소 |
| ------ | -- | ----------- |
| 최애림 | 탐색적 분석, 데이터 전처리, 이미지 패치화 및 롱루 모델링, 발표 | https://github.com/choi-aerim |
| 이정현 | 탐색적 분석, 데이터 전처리, 전체 모델링 및 사전 학습 모델 비교, FPN 모델링 | https://github.com/leejunghyunA |
| 윤정준 | 탐색적 분석, 데이터 전처리, 전체 모델링 및 사전 학습 모델 비교 | |
| 진청아 | 탐색적 분석, 데이터 전처리, 전체 모델링 및 사전 학습 모델 비교 | https://github.com/risa1796 |

<br/>

# 🌱 요약

림프절(임파선)은 암의 전이, 암이 퍼지는 데 매우 치명적인 역할을 하기 때문에 림프절 전이 여부와 전이 단계를 빠르고 정확하게 파악하는게 매우 중요합니다. 병리 슬라이드 이미지내의 조직을 분석하여 전이 여부를 판단하는 방법으로 병리학자가 얼마나 정확하고 빨리 진단을 내리는지가 핵심입니다. 그러나 기존에 병리 학자가 직접 확인하여 진행하던 방식은 사람이 하는 한계로 진단하기까지 시간이 소요되고 사람마다 다른 결과로 예측할 수 있습니다. 공모전에서 제공한 병리 슬라이드 이미지와 정형데이터를 사용하여 유방암 임파선 전이 예측 모델을 개발을 목표로 하여, 정확한 예측이 가능하다면 짧은 시간에 보다 적은 비용으로 객관적인 판단을 내릴 수 있습니다. 이를 통해 환자에게 보다 빠르고 정확한 진단 및 맞춤 치료 방향 수립할 수 있게 됩니다. 

공모전 링크 : https://dacon.io/competitions/official/236011/overview/description

## 사용한 모듈
- 언어 <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/>
- 구축환경 <img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/> 
- 활용 기술  <img src="https://img.shields.io/badge/Pycaret-3776AB?"/>
- 통합 개발 환경 <img src="https://img.shields.io/badge/Anaconda-44A833?style=flat-square&logo=Anaconda&logoColor=black"/> <img src="https://img.shields.io/badge/Jupyter Notebook-F37626?style=flat-square&logo=Jupyter&logoColor=black"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=black"/> <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-D00000?style=flat-square&logo=PyTorch&logoColor=white"/> 



<br/>

# 📣 과정


| Week | 코드 | 내용|
| ------ | -- | ----------- |
| 1주차 | ☑️ | 리서치 및 비정형 데이터 탐색적 분석 |
| 2주차 | ☑️ | 전체 모델링 및 사전 학습 모델간 결과 비교 |
| 3주차 | ☑️ | 이미지 패치화  |
| 4주차 | ☑️ | FPN 모델 |
| 5주차 | ☑️ | 이미지 모델간 결과 비교 및 시각화 |
| 6주차 | ☑️ | 결과 시각화 및 발표 준비  |

<br/>

# 💬 팀원들의 후기

| 팀원 | 아쉬웠던 점| 
| ------ | -- | 
| 최애림 | 이미지 마스킹 처리를 시도한 부분에서 불균형 패치 수 조절, 다양한 크기의 이미지를 패치화해서 시도하지 못했던 점, 컴퓨터 성능 문제로  비용이 큰 pretrain된 모델 및 하이퍼파라미터 적용하지 못한 점이 아쉬웠습니다. | 
| 이정현 | 병리슬라이드가 큰 사이즈로 구성되어있어 이를 input사이즈에 맞게 축소시켰을 때, 정확한 특징을 찾아내지 못한 부분과 제공된 마스킹데이터를 활용해 다양한 방법으로 이미지 데이터를 처리하고 싶었으나, 컴퓨터의 성능 문제로 시도도하지 못한 부분이 많아 아쉬웠습니다. 그렇지만 이미지 처리 과정에서 실제 데이터를 적용시키고 그 결과를 확인하면서 모델을 이해하는데 많은 도움이 되었습니다. |
| 윤정준 | 컴퓨터의 성능이 부족하여 좀 더 많은 비용이 소모되는 모델 및 더 많은 하이퍼 파라미터의 시행을 못해 보았으며 단순히 비용이 큰 모델뿐만 아니라 큰 이미지로 인한 메모리 부족으로 시행 조차 하지 못한 부분들이 아쉬웠습니다. Dacon에서 제공한 마스킹 데이터를 보고 딥러닝을 사용하여 마스킹 데이터를 생성하려고 하였으나 원하는 정도의 성과가 나오지 않아 이미지 전처리로 전이를 예측한 부분이 아쉬웠습니다.| 
| 진청아 | 다양한 접근 방식으로 높은 해상도의 병리 조직 슬라이드 이미지를 분석하고자 했으나, 적은 병리 슬라이드 이미지 개수와 annotation(주석) 데이터 부족으로 발생한 과적합을 해결하는데 상당한 어려움이 있었습니다. | 

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FleejunghyunA%2Fthird_project&count_bg=%23D54A1C&title_bg=%23555555&icon=myspace.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
