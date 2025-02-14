# Jetson Nano 영상처리를 활용한 AI 무인차량 제작

> 주행로봇 전면에 연결된 카메라를 통해 이미지 데이터를 수집  
> neural network 학습을 통해 주행 데이터 및 시나리오 학습  
> 자율주행 중 카메라로 인식된 데이터를 실시간으로 식별하여 학습된 시나리오를 기반으로 따라갈 수 있도록   

<img src="docs/images/waveshare_jetbot_green.jpg" height="256">

JetBot은 NVIDIA Jetson Nano를 기반으로 카트의 형태로 제작 할 수 있는 카트 입니다. 

## 사용된 장비와 기술
* **Pytorch** - Python 3.x 기반으로 GPU에서 텐서 조작 및 동적 신경망 구축이 가능한 프레임워크 사용, 선형 회귀와 자동 미분이 특징 
* **CUDA** - GPU의 병렬 연산을 API 방식으로 공개하여 개발자가 Nvidia의 그래픽 연산 장치를 사용할 수 있도록 한 toolkit
* **Jetson Nano, 외부 그래픽 카드 GTX 1060 3GB** - 학습을 위한 데이터로 신경망 학습을 위해 Nvidia 사의 그래픽 연산 장치를 사용
* **JetBot** - 카메라, 무선 통신, 바퀴, 차체 등을 Jetson Nano에 조립할 수 있는 AI Robot 키트

Building and using JetBot gives the hands on experience needed to create entirely new AI projects.

To get started, read the [JetBot documentation](https://jetbot.org).

## Get involved

We really appreciate any feedback related to JetBot, and also just enjoy seeing what you're working on!  There is a growing community of Jetson Nano and JetBot users.  It's easy to get involved involved...

<!--* Join the [chat server](https://discord.gg/Ady6NtF)-->
* Ask a question and discuss JetBot related topics on the [JetBot GitHub Discussions](https://github.com/NVIDIA-AI-IOT/jetbot/discussions)
* Report a bug by [creating an issue](https://github.com/NVIDIA-AI-IOT/jetbot/issues)
* Share your project or ask a question on the [Jetson Developer Forums](https://devtalk.nvidia.com/default/board/139/jetson-embedded-systems/)
## 인공신경망 학습

[Train Model](notebooks/road_following/train_model.ipynb)  
[Live Driving](notebooks/road_following/live_demo.ipynb)
