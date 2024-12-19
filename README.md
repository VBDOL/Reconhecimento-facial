# Criando um Sistema de Reconhecimento Facial do Zero

## Descrição do Projeto

O objetivo principal deste projeto é trabalhar com as bibliotecas e frameworks estudados em nossas aulas para criar um sistema de detecção e reconhecimento de faces. Utilizaremos o framework TensorFlow em conjunto com outras bibliotecas necessárias. O sistema deve ser capaz de detectar e reconhecer múltiplas faces simultaneamente.

![Figura 1: Detecção e reconhecimento facial](caminho/para/sua/imagem.png)

## Requisitos

- TensorFlow
- OpenCV
- dlib
- NumPy
- Outros pacotes que julgue necessário

## Passos para Implementação

### 1. Detecção Facial

Utilize uma rede de detecção treinada para detectar faces. Uma boa referência é o trabalho de detecção facial disponível [aqui](https://colab.research.google.com/drive/1QnC7lV7oVFk5OZCm75fqbLAfD9qBy9bw?usp=sharing).

### 2. Classificação Facial

Utilize uma rede de classificação para reconhecer a face detectada. Você pode utilizar o exemplo de detecção e classificação de objetos disponível [aqui](https://colab.research.google.com/drive/1xdjyBiY75MAVRSjgmiqI7pbRLn58VrbE?usp=sharing).

### 3. Pré-processamento das Imagens

- Carregar imagens
- Detectar faces nas imagens
- Alinhar e redimensionar as faces detectadas

### 4. Treinamento do Modelo

- Treinar uma rede de detecção de faces
- Treinar uma rede de classificação de faces

### 5. Integração e Avaliação

- Integrar os modelos de detecção e classificação
- Testar o sistema em novas imagens


