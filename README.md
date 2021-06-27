# MAC5768_EPs

Repositório da matéria de Visão e Processamento de Imagens - USP - 2021-1

## Integrantes

- Amanda Cristina Mazer - NUSP: 10200951
- Carlos Alberto Silva de Souza - NUSP: 8539408
- Leonardo Miranda de Brito - NUSP: 12630364

## Links Importantes:

- Link para o notebook no Google Colab do EP1: https://colab.research.google.com/drive/15zsFuqjrjg46MjU7dnI0LvtgE9ji8jzm
- Link para o notebook no Google Colab do EP2.1: https://colab.research.google.com/drive/1h6i3BKGLtBKLcju-Sy6PT2kUJ5kvKbRv
- Link para o notebook no Google Colab do EP2.2: https://colab.research.google.com/drive/11gNBb9oQxITN8QViUZ0b7m5CgpaJc4bv#scrollTo=Xf133sTKPpGw
- Link para a pasta do Google Drive: https://drive.google.com/drive/u/0/folders/1WEzT7nZTrtw9EBntSM8hCzoGQyDAQUIw

## EP01 - Descrição
O Exercício Programa 1 consiste em:
- Criar uma base de imagens e;
- Escrever um notebook em python contendo os metadados das imagens, tabela global sumária, tabela detalhada por classe e uma apresentação das imagens em um formato MNIST-like.

## EP02 - Descrição
### EP02.1: Data Augmentation
O Exercício Programa 2.1 consiste em:
- Criar um JN contendo funções para fazer data augmentation do dataset do EP1;
- Criar 5 funções de data augmentation. Cada função será aplicada a cada imagem do dataset do EP1, sendo estas funções:
  - RGB2gray (ie converter as imagens RGB originais em níveis de cinza);
  - Soma de fundo com gradiente de níveis de cinza;
  - Logaritmo da imagem;
  - Exponencial da imagem;
  - Filtro da média implementado usando convolução;
- Salvar essas alterações em pastas no drive.

### EP02.2: Data Augmentation
O Exercício Programa 2.2 consiste em:
- Criar um JN que realize a normalização das imagens de cada classe do dataset de augmentation;
- Usar a equalização de histogramas como função inicial de normalização, gerando um normalizedDataset;
- Aplicar as seguintes funções de análise à cada classe presente nos datasets originalGrayDataset, augmentedDataset e normalizedDataset:  
  - Protótipo médio de cada classe;
  - Histograma médio de cada classe;
  - Variância do histograma de cada classe.
