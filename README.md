# Sistema de Manipulação e Processamento Avançado de Imagens com OpenCV

Este projeto implementa uma série de técnicas de manipulação e processamento de imagens usando a biblioteca OpenCV em Python. O sistema oferece funcionalidades como leitura e exibição de imagens, pré-processamento, aplicação de filtros, detecção de características, transformações geométricas, operações morfológicas e análise de imagens.

## Funcionalidades Implementadas

1. **Leitura e Exibição de Imagens**
   - Carrega imagens e  m diferentes formatos (JPEG, PNG, BMP) e exibe na tela.

2. **Pré-processamento de Imagens**
   - Conversão de cores (RGB para Grayscale)
   - Redimensionamento de imagens
   - Equalização de histograma para melhorar o contraste

3. **Aplicação de Filtros**
   - Filtros de desfoque (GaussianBlur)
   - Detecção de bordas (Canny, Sobel)

4. **Detecção de Características**
   - Detecção de cantos (Harris)
   - Detecção de contornos

5. **Transformações Geométricas**
   - Rotação de imagens

6. **Operações Morfológicas**
   - Erosão e dilatação de imagens
   - Segmentação de objetos

7. **Segmentação de Imagens**
   - Limiarização (Thresholding)
   - Algoritmo Watershed para segmentação de imagens

8. **Combinação e Operações Aritméticas em Imagens**
   - Soma e subtração de imagens
   - Blending de imagens
   - Image stitching para combinar múltiplas imagens

9. **Análise de Imagens**
   - Análise de formas (área, perímetro)
   - Análise de textura usando Local Binary Patterns (LBP)

10. **Manipulação de Arquivos**
    - Salvamento de imagens processadas em diferentes formatos

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/antoniofelipe-dev/sistemaManipulacaoImg.git
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Referências

- [Documentação do OpenCV](https://docs.opencv.org/)
- [Tutoriais OpenCV Python](https://opencv-python-tutroals.readthedocs.io/)
