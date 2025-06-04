# Homer vs Bart — Classificação de Imagens com CNN
![Status](https://img.shields.io/badge/status-Finalizado-brightgreen)
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Keras](https://img.shields.io/badge/Keras-TensorFlow-red?logo=keras)


Este projeto aplica uma rede neural convolucional (CNN) para classificar imagens dos personagens Homer e Bart Simpson. A rede foi desenvolvida em Python com TensorFlow/Keras, utilizando um dataset personalizado com imagens de ambos os personagens.

## Objetivo

Desenvolver um modelo de deep learning capaz de identificar, com alto grau de acurácia, se uma imagem pertence ao Homer ou ao Bart. O projeto envolve desde o pré-processamento do dataset até a inferência em imagens externas obtidas da internet.

## Etapas do Projeto

- **Pré-processamento de imagens**
  - Redimensionamento (64x64) e normalização
  - Separação em conjuntos de treino e teste com `ImageDataGenerator`
- **Construção da arquitetura CNN**
  - Camadas convolucionais (`Conv2D`), pooling (`MaxPooling2D`)
  - Camada `Flatten`, `Dense`, `Dropout` para evitar overfitting
- **Treinamento e avaliação**
  - Acurácia e perda monitoradas com gráficos de desempenho
- **Inferência**
  - Upload de imagem externa para predição com o modelo treinado

## Resultados

- Acurácia final obtida: **84.93%**
- O modelo foi testado com imagens externas e classificou corretamente.

## Tecnologias Utilizadas

- Python 3.11
- Google Colab
- TensorFlow / Keras
- NumPy
- Matplotlib

## Arquivos

- `Checkpoint5_CNN_Homer_Bart.ipynb` — Notebook com o pipeline completo
- `README.md` — Este arquivo de descrição do projeto
