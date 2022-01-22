FROM  pytorch/pytorch:1.10.0-cuda11.3-cudnn8-devel

RUN python -m pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu111/torch1.10/index.html

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install ffmpeg libsm6 libxext6 python3-tk -y

RUN pip install pandas opencv-python munkres
