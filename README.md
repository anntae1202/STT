# STT
wav2vec2를 활용한 Speech to Text


한국어 전용 stt모델 개발을 위해
huggingface의 wav2vec2를 사용.


다양한 데이터셋을 변경해가며 학습.

좋은 장비 덕분에 오랜시간 학습이 가능했다.

가상환경 : docker 컨테이너 환경 구축

>> docker pull dzw001/cuda11.1-cudnn8-python3.6-pytorch1.8.1-ubuntu18.04



서버 : V100

데이터셋 : AI-hub의 ktalk 한국어 일상 대화 데이터셋
