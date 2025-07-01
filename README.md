Helmet Detection with YOLOv8

<p align="center"> <img src="https://img.shields.io/badge/YOLOv8-Object%20Detection-green?style=flat-square"/> <img src="https://img.shields.io/badge/Python-3.11-blue?style=flat-square"/> <img src="https://img.shields.io/badge/Colab-GPU-yellow?style=flat-square"/> </p>

Descrição:

Este projeto tem como objetivo implementar um sistema de detecção de capacetes em motociclistas usando o modelo YOLOv8. A aplicação inclui:
Treinamento supervisionado em imagens, Avaliação do modelo com métricas quantitativas (mAP, matriz de confusão), Predição em imagens aleatórias e vídeos.
Projeto desenvolvido como parte da disciplina Segmentação e Estrutura de Reconhecimento de Padrões Contextualizada.

Tecnologias e ferramentas: 
- Python 3.11

- YOLOv8 (Ultralytics)

- Torch

- OpenCV

- MoviePy

- Google Colab (execução do notebook

Dataset
📦 Dataset: Helmet Detection (Kaggle)

Classes:

- 0: rider

- 1: helmet

- 2: no_helmet

Pré-requisitos
- Conta no Google Colab ou ambiente local com GPU CUDA configurada.

- Chave de API do Kaggle (kaggle.json) para download do dataset.

- Clone ou faça upload do notebook Helmet_Detection.ipynb para o Google Colab.