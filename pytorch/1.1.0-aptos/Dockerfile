FROM pytorch/pytorch:1.1.0-cuda10.0-cudnn7.5-runtime

RUN set -x && \
    apt-get update && \
    apt-get install -y libglib2.0-0 libsm6 libxext6 libxrender1 libfontconfig1 && \
    apt-get install -y vim-common && \
    apt-get install -y zip && \
    git clone https://github.com/NVIDIA/apex && \
    cd apex && \
    pip install -v --no-cache-dir ./ && \
    cd ../ && \
    pip install --upgrade pip && \
    pip install pillow && \
    pip install opencv-python && \
    pip install opencv-contrib-python && \
    pip install absl-py && \
    pip install xlrd && \
    pip install tensorboard==1.14.0 && \
    pip install fastai==1.0.55 && \
    pip install tqdm==4.32.1 && \
    pip install scipy==1.2.1 && \
    pip install scikit-image==0.15.0 && \
    pip install scikit-learn==0.21.2 && \
    pip install pandas==0.23.4 && \
    pip install matplotlib==3.0.3 && \
    pip install seaborn==0.9.0 && \
    pip install imgaug==0.2.6 && \
    pip install --upgrade efficientnet-pytorch && \
    pip install future && \
    pip install Kaggle
