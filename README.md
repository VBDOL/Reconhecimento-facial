# Sistema de Reconhecimento Facial com MTCNN e TensorFlow

## Descrição do Projeto

O objetivo deste projeto é criar um sistema de reconhecimento facial do zero, utilizando bibliotecas e frameworks estudados durante as aulas. O sistema deve ser capaz de detectar e reconhecer múltiplas faces em uma imagem ao mesmo tempo. Para isso, foram utilizadas as bibliotecas TensorFlow, OpenCV, NumPy e MTCNN.

## Instalação de Dependências

Para executar o projeto no ambiente Google Colab, é necessário instalar as dependências `mtcnn` e `opencv-python-headless`. Essas bibliotecas são essenciais para a detecção e o processamento de imagens.

## Etapas do Projeto

### 1. Importação de Bibliotecas e Configuração Inicial

Nesta etapa, são importadas todas as bibliotecas necessárias para o projeto, incluindo TensorFlow para o reconhecimento facial, OpenCV para o processamento de imagens, NumPy para manipulação de arrays, matplotlib para exibição de imagens, e MTCNN para detecção facial.

### 2. Carregamento e Exibição de Imagens

Funções foram desenvolvidas para carregar e exibir imagens. O carregamento é feito com a biblioteca OpenCV, e a exibição das imagens é feita com matplotlib para melhor visualização dos resultados.

### 3. Detecção Facial com MTCNN

Utiliza-se a biblioteca MTCNN para detectar faces nas imagens. A MTCNN é uma rede neural treinada para identificar rostos em diferentes posições e iluminações. Faces detectadas com confiança maior que 90% são marcadas com retângulos verdes na imagem.

### 4. Reconhecimento Facial

Para o reconhecimento facial, é utilizada uma rede neural pré-treinada (exemplo: FaceNet) que gera embeddings das faces detectadas. Esses embeddings são vetores que representam características únicas de cada rosto, permitindo a identificação e classificação das faces.

### 5. Integração: Detecção e Reconhecimento

As etapas de detecção e reconhecimento facial são integradas para processar uma imagem de entrada, detectar as faces presentes, gerar embeddings para essas faces e exibir os resultados. O processo é executado de forma sequencial, desde o carregamento da imagem até a exibição das faces reconhecidas.

### 6. Execução Principal

No bloco principal, são definidos os caminhos para a imagem de entrada e o modelo de reconhecimento facial. A função principal do projeto é chamada para processar a imagem e exibir os resultados.

## Resultados Esperados

### Imagem Original
Nesta seção, a imagem original carregada pelo sistema será apresentada.

![Imagem Original](caminho/para/imagem_original.png)

### Detecção Facial
Aqui será exibida a imagem com a detecção facial aplicada, mostrando as faces detectadas com retângulos verdes ao redor.

![Detecção Facial](caminho/para/imagem_detectada.png)

## Conclusão

Este projeto demonstra a aplicação prática de técnicas de visão computacional para a criação de um sistema de reconhecimento facial. Utilizando bibliotecas poderosas como TensorFlow e MTCNN, foi possível desenvolver um sistema capaz de detectar e reconhecer múltiplas faces em uma imagem, mostrando o potencial dessas ferramentas para aplicações reais.

---
