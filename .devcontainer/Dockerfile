FROM mcr.microsoft.com/devcontainers/anaconda:3

RUN pip install pip --upgrade
RUN pip install pyopenssl --upgrade

# Install libs
RUN conda install -c conda-forge pytorch-lightning
RUN pip install matplotlib numpy pillow pandas sklearn