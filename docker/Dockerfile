FROM nvcr.io/nvidia/pytorch:21.09-py3

RUN apt update && apt install -y \
    build-essential \
    libgl1-mesa-glx

RUN git clone https://github.com/cameronchoi/r3det-on-mmdetection.git /r3det-on-mmdetection
WORKDIR /r3det-on-mmdetection
RUN pip install --no-cache-dir -e .
