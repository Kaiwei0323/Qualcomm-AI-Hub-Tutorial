# Qualcomm-AI-Hub-Tutorial

## Prerequisites
* OS: Ubuntu 22.04
* Model: yolov5.onnx

## Navigate to Qualcomm AI Hub
* [Qualcomm AI Hub](https://aihub.qualcomm.com/)

## Sign Up for Qualcomm Account

## Get your API Token
* Once signed in navigate to Account -> Settings -> API Token

## Environment Setup
```
conda create python=3.8 -n qai_hub
conda activate qai_hub
pip3 install qai-hub
qai-hub configure --api_token INSERT_API_TOKEN
```
## Run Jupyter Notebook
```
git clone https://github.com/Kaiwei0323/Qualcomm-AI-Hub-Tutorial.git
jupyter notebook
```
