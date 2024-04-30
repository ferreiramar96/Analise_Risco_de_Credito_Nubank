[![author](https://img.shields.io/badge/author-felipeferreira-red.svg)](https://www.linkedin.com/in/felipeferreiratids/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/ferreiramar96/Data_Science)

<p align="center">
  <img src="https://raw.githubusercontent.com/ferreiramar96/Analise_Risco_de_Credito_Nubank/main/Imagens/capa.png" alt="imagem maneira relacionada ao projeto"height=420px >
</p>

## Análise de Risco de Crédito - Nubank
Nesse projeto utilizei os dados de uma competição realizada pela Startup Nubank, no qual o objetivo seria criar um modelo de Machine Learning que forneça a probabilidade de um cliente se tornar inadimplente, esperando que o modelo seja capaz de minimizar as perdas financeiras do Nubank, porém minimizando também os falsos positivos. Ao longo de todo o projeto é realizado um storytelling com detalhes ricos e uma bela ilustração.

Realizei uma análise exploratória completa, tanto para análisar a qualidade de nossos dados, quanto para entender mais afundo as questões do negócio e poder agregar mais valor. E também pude verificar algumas hipóteses, tais como: A maioria dos clientes possuiam facebook, se a região que mais possuía cliente era a Sudeste e entre outras... E respondi todas essa hipóteses utilizando os dados e gráficos para o melhor entendimento.  

Logo de cara assim que plotei um gráfico com os dados das vendas ao longo do tempo, percebi que estávamos lidando com uma *Série Temporal* pois havia tendência e sazonalidade, e para utilizarmos nossos algoritmos para fazer a previsão, é preciso que nossa Série Temporal seja estacionária e então realizei o teste ADF. Após o teste o resultado nos indica que nossa série não é estacionária, e então precisei fazer algumas transformações para torna-la estacionária, como: logaritma, subtração da média móvel e diferenciação.

Agora com os dados corretos e a série temporal estacionária, comecei com nossos modelos de machine learning e os que utilizei foram: Pycaret, Holt's Linear Trend Model, Arima e Prophet. Após o treinamento dos modelos é a hora de avaliarmos, porém antes de avaliar precisei fazer a reversão dos dados da série temporal, pois os resultados de alguns algoritmos estavam em escalas diferente, e com isso não era possível avaliar de forma correta o algoritmo.

Com tudo pronto, fui para a avaliação de todos os modelos e a métrica escolhida foi o *MAPE (mean absolute percentage error)*, e o algoritmo que obteve um melhor resultado com nossos dados de teste foi o ARIMA com 2.16% de erro médio.

A seguir, alguns pontos do projeto:
* Análise exploratória para entender os dados
* Modelagem dos dados
* Feature Engineering
* Business Understanding
* Transformações da Série Temporal para estacionária
* Treinamento de vários algoritmos
* Reversão das transformações na ST
* Avaliação dos resultados e conclusão

Ao longo de todo o projeto, cada célula de código está explicada para uma fácil compreensão, acompanhado de um belo storytelling. Vocês também encontrarão algumas análises estatísticas, histogramas, matriz de correlação e toda a parte de pré-processamento dos dados, desde as análises até a avaliação dos modelos.

Neste projeto foi utilizado: Storytelling, Estatística, Série Temporal, Python, Machine Learning e Modelagem de Dados e Matemática.


[Link para o projeto completo](https://github.com/ferreiramar96/Previsao_Demanda_Vinhos_Time_Series/blob/main/Previs%C3%A3o_de_Demanda_Vinhos_(S%C3%A9rie_Temporal).ipynb)

**Links para me acharem:**
* [Artigo desse projeto no Linkedin](https://www.linkedin.com/feed/update/urn:li:activity:7141405755013869568/)
* [LinkedIn](https://www.linkedin.com/in/felipeferreiratids/)
* [Instagram](https://www.instagram.com/ferreiramar96/)
* [Portfólio Completo](https://github.com/ferreiramar96/Data_Science)
