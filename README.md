# Detecção de Rostos com MTCNN
Este projeto utiliza a técnica de detecção de rostos com a rede neural MTCNN (Multi-task Cascaded Convolutional Networks) para identificar rostos em imagens. A solução foi desenvolvida com as bibliotecas OpenCV, MTCNN e TensorFlow.

## Funcionalidades
Baixar uma imagem da web a partir de uma URL fornecida.
Carregar e exibir a imagem utilizando o OpenCV e Matplotlib.
Detectar rostos na imagem usando a biblioteca MTCNN.
Exibir a imagem com as faces detectadas destacadas por retângulos.

## Pré-requisitos
Para executar este código, você precisará das seguintes bibliotecas:

opencv-python: Para manipulação de imagens.
mtcnn: Para detecção de rostos.
tensorflow: Para outras possíveis expansões do código (não utilizado diretamente neste exemplo).
urllib: Para baixar imagens da web.
Você pode instalar essas dependências utilizando o seguinte comando:

pip install opencv-python mtcnn tensorflow

Além disso, para a detecção de rostos, as bibliotecas mtcnn e lz4 precisam ser instaladas:

pip install mtcnn
pip install lz4

##Como Usar

Passo 1: Instalar as dependências
Primeiro, instale as bibliotecas necessárias com o comando acima.

Passo 2: Baixar e exibir a imagem
A imagem será baixada de uma URL e exibida em seu notebook Jupyter.

Passo 3: Detectar rostos
Com a biblioteca MTCNN, os rostos presentes na imagem serão detectados e destacados com retângulos verdes. O código mostra a imagem resultante após a detecção de rostos.

##Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
