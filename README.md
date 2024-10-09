# Sistema de Manipulação e Processamento de Imagens com OpenCV

Este projeto implementa uma série de técnicas de manipulação e processamento de imagens usando a biblioteca OpenCV em Python. Ele oferece funcionalidades como leitura e exibição de imagens, pré-processamento, aplicação de filtros, detecção de características, transformações geométricas, operações morfológicas e análise de imagens.

## Funcionalidades Implementadas

1. **Leitura e Exibição de Imagens**
   - Carrega e exibe imagens nos formatos (JPEG, PNG, BMP).

2. **Pré-processamento de Imagens**
   - Conversão de cores (RGB para Grayscale).
   - Redimensionamento de imagens.
   - Equalização de histograma para melhorar o contraste.

3. **Aplicação de Filtros**
   - Filtros de desfoque (GaussianBlur).
   - Detecção de bordas (Canny, Sobel).

4. **Detecção de Características**
   - Detecção de cantos (Harris).
   - Detecção de contornos.

5. **Transformações Geométricas**
   - Rotação de imagens.

6. **Operações Morfológicas**
   - Erosão e dilatação de imagens.
   - Segmentação de objetos.

7. **Segmentação de Imagens**
   - Algoritmo Watershed para segmentação.

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/antoniofelipe-dev/sistemaManipulacaoImg.git
    ```

2. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

## Utilização

### Leitura e Exibição de Imagens

```python
import cv2
import matplotlib.pyplot as plt

# Carregar imagem
image = cv2.imread('./assets/lula.png')

# Exibir imagem
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))
plt.axis('off')
plt.show()
