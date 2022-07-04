# Exercício de Precificação de Imóveis

Projeto com objetivo de praticar e revisar Regressão Linear através da precificação de imóveis.

O estudo foi feito com base em exercícios prévios:
* Curso de Regressão Linear: testando relações e prevendo resultados (Alura), onde foi desenvolvido um modelo de regressão linear sobre o consumo de cerveja ao longo de um ano.
* 4ª Imersão Dados (Alura), com desenvolvimento de um modelo de precificação de imóveis em uma base de dados reais de São Paulo
[Link do projeto](https://github.com/Tathy/Pesquisa-Imoveis-SP)

Dataset: https://www.kaggle.com/greenwing1985/housepricing

O imóveis e preços são fictícios, com finalidade de prática de Python e modelos de Machine Learning.

O dataset possui, principalmente, informações físicas sobre imóveis e preços. A única característica de localização são três cidades em que os imóveis são distribuídos, sem informações relacionadas a qualidade de vida ou vizinhança.

## Principais observações

Como é um conjunto gerado computacionalmente para fins de prática e fixação de conceitos, é esperado que o uso direto de todas as variáveis explicativas gerem previsões com 100% de acerto, o que não seria observado em uma situação com dados reais.

Os estudos sobre o segundo modelo mostram o que seria desejável em qualquer dataset, como se comportariam as métricas de regressão e o gráfico de dispersão em uma predição 100% correta.

### Métricas de regressão

As métricas usadas para avaliação foram Coeficiente de Determinação (R²), Erro Quadrático Médio (EQM) e a Raiz do Erro Quadrático Médio (REQM). Como o segundo modelo mostra uma predição perfeita, os valores encontrados foram os melhores possíveis.

### Gráfico de Dispersão ideal

<div align="center">
  <img src="https://github.com/Tathy/Precificacao-imoveis/blob/main/images/grafico_dispersao.png?raw=true"/>
</div>
