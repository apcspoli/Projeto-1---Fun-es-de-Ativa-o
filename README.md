# Neste projeto, utilizaremos Redes Neurais Artificiais (MLP) com o dataset MNIST, que contém imagens de dígitos manuscritos de 0 a 9. O objetivo principal é aplicar técnicas de RNA para classificação supervisionada, explorando a comparação entre ReLU, Sigmoid e Tanh em redes com 1 ou mais camadas ocultas e aplicar ruído gaussiano aos dígitos e analisar o impacto da ativação na robustez e acurácia.

Para executar o código basta exportar para a ferramenta collab, e executar na sequência informada nos comentários do código:

![image](https://github.com/user-attachments/assets/1291de7b-7721-4e9f-ab66-1551ae0b0faf)


As bibliotecas utilizadas foram:

```

import tensorflow as tf
from tensorflow.keras.models import Sequential  # Modelo sequencial (camadas empilhadas)
from tensorflow.keras.layers import Dense, Flatten, GaussianNoise  # Tipos de camadas utilizadas
from tensorflow.keras.datasets import mnist  # Dataset MNIST (imagens de dígitos escritos à mão)
from tensorflow.keras.utils import to_categorical  # Para converter rótulos em codificação one-hot
from sklearn.metrics import confusion_matrix  # Para gerar matriz de confusão

import seaborn as sns  # Biblioteca para visualização de dados (gráficos)
import matplotlib.pyplot as plt  # Biblioteca para gráficos
import numpy as np  # Biblioteca para operações numéricas
import pandas as pd  # Biblioteca para manipulação de dados tabulares

```
