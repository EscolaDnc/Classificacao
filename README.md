Este projeto tem como objetivo explorar e analisar diferentes conjuntos de dados para exercitar habilidades de manipulação, visualização e modelagem de dados. Como os datasets utilizados são grandes, eles não foram incluídos diretamente no repositório. Em vez disso, os alunos devem baixá-los manualmente das fontes indicadas abaixo.

Como Obter os Datasets

1. Spotify Hits

Fonte: KaggleLink para download: Spotify Hits no Kaggle

Acesse o link acima e procure pelo dataset "Spotify Hits".

Baixe o arquivo e extraia o conteúdo.

Salve os arquivos na pasta data/spotify_hits/ dentro do repositório local.

2. US Accidents

Fonte: KaggleLink para download: US Accidents no Kaggle

Acesse o link acima e procure pelo dataset "US Accidents".

Baixe o arquivo e extraia o conteúdo.

Salve os arquivos na pasta data/us_accidents/ dentro do repositório local.

3. Câncer de Mama (Breast Cancer Dataset)

Fonte: Scikit-learn (embutido na biblioteca)

Este dataset já está disponível diretamente na biblioteca scikit-learn e pode ser carregado com o seguinte código Python:

from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()
X, y = data.data, data.target
print(data.DESCR)

Estrutura do Projeto

A estrutura de pastas recomendada para o projeto é a seguinte:
