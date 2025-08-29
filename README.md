# vllm-install-notebook
vllm-install-notebook


## install stable vllm---python=3.12


* pip install vllm
* pip list|grep torch
* pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu128 -U
* fixed version ->pip install torch==2.7.1 torchvision==0.22.1 torchaudio==2.7.1 --index-url https://download.pytorch.org/whl/cu128 -U
* pip install vllm[flashinfer]