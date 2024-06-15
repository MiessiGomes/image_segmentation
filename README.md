# Projeto de Segmentação de Imagem usando KMeans

Este projeto é sobre a segmentação de imagens usando o algoritmo KMeans. O objetivo é dividir uma imagem em diferentes segmentos ou clusters.

## Bibliotecas Utilizadas

As seguintes bibliotecas foram utilizadas neste projeto:

* `cv2`: Para manipulação de imagens.
* `numpy`: Para operações matemáticas e manipulação de arrays.
* `matplotlib`: Para visualização de dados e imagens.
* `sklearn`: Para implementação do algoritmo KMeans.

## Processo

1. **Importação da imagem**: A imagem a ser segmentada é importada usando a biblioteca `cv2`.

2. **Redimensionamento da imagem**: A imagem é redimensionada para uma largura e altura específica usando a função 'resize' da biblioteca `cv2`.

3. **Preparação dos dados da imagem**: A imagem é convertida em um array 2D para ser usada no algoritmo KMeans.

4. **Aplicação do KMeans**: O algoritmo KMeans é aplicado na imagem com um número de clusters variando de 2 a 30.

5. **Visualização da inércia**: A inércia é visualizada usando o método do cotovelo para identificar o número ideal de clusters a ser usado.

6. **Segmentação da imagem**: A imagem é segmentada usando o número ideal de clusters identificado.

7. **Comparação com a imagem original**: A imagem segmentada é comparada com a imagem original para visualizar os resultados.

## Resultados

Os resultados mostram que a segmentação de imagens usando o algoritmo KMeans pode ser uma ferramenta eficaz para a análise e processamento de imagens. A segmentação permite a identificação de diferentes partes de uma imagem e pode ser útil em várias aplicações, como reconhecimento de objetos, rastreamento de objetos, análise de imagens médicas, entre outros.
