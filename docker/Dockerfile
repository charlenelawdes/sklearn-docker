FROM debian:11

RUN apt-get update && apt-get install -y \
    gcc \
    make \
    python3 \
    cython3 \
    python3-numpy \
    python3-pip \
    python3-scipy \
    python3-joblib

RUN pip3 install -U scikit-learn==0.21.3
