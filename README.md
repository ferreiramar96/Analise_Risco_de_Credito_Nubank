[![author](https://img.shields.io/badge/author-felipeferreira-red.svg)](https://www.linkedin.com/in/felipeferreiratids/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/ferreiramar96/Data_Science)

<p align="center">
  <img src="https://raw.githubusercontent.com/ferreiramar96/Analise_Risco_de_Credito_Nubank/main/Imagens/capa.png" alt="imagem maneira relacionada ao projeto"height=420px >
</p>

## Análise de Risco de Crédito - Nubank
Nesse projeto utilizei os dados de uma competição realizada pela Startup Nubank, no qual o objetivo seria criar um modelo de Machine Learning que forneça a probabilidade de um cliente se tornar inadimplente, esperando que o modelo seja capaz de minimizar as perdas financeiras do Nubank, porém minimizando também os falsos positivos. Ao longo de todo o projeto é realizado um storytelling com detalhes ricos e uma bela ilustração.

Realizei uma análise exploratória completa, tanto para análisar a qualidade de nossos dados, quanto para entender mais afundo as questões do negócio e poder agregar mais valor. E também pude verificar algumas hipóteses, tais como: A maioria dos clientes possuiam facebook, se a região que mais possuía cliente era a Sudeste e entre outras... E respondi todas essa hipóteses utilizando os dados e gráficos para o melhor entendimento.  

Após realizar as análises e aplicar algumas transformações aos dados, comecei e pensar em como e quais algoritmos poderia utilizar para este problema. E como dito anteriormente, nosso objetivo é criar um modelo para fornecer probabilidades, então estamos falando de um problema de Classificação. Antes de criar o modelo, observei que seria necessário aplicar alguns Pré-Processamentos aos dados, tais como: Codificação, Escalonamento, Feature Engineer e Redução de Dimensionalidade (PCA).

Agora com os dados corretos, comecei com nossos modelos de machine learning e os que utilizei foram: Regressão Logística, Random Forest, Árvore de Decisão, KNN, SVM, Naive Bayes, Gradiente Descendente, XGBoost e LightGBM. Após o treinamento dos modelos é a hora de avaliarmos. A métrica escolhida foi o *Recall*, escolhi os 3 algoritmos que obtiveram **os melhores resultados e foram: Regressão Logística(65.67%), LightGBM(65.41%) e Random Forest(64.65%)**. Sendo o algoritmo de pior desempenho o Naive Bayes(34.67%). É importante ressaltar também que fiz o treinamento em 2 conjunto de dados com os dados de dimensionalidades originais e com a redução, e os originais obtiveram um melhor resultado como podem ver a seguir:

<p align="center">
  <img src="https://raw.githubusercontent.com/ferreiramar96/Analise_Risco_de_Credito_Nubank/main/Imagens/resultado_modelospng.png" alt="imagem maneira relacionada ao projeto"height=300px >
</p>

Sabendo quais modelos obtiveram os melhores resultados, fui para a tunagem de hiperparâmetros com o objetivo de melhorar ainda mais o nosso reultado. Após a tunagem consegui melhores valores, e apliquei os modelos finais aos dados de teste. E para tirar a dúvida para saber se de fato a tunagem dos hiperparâmetros foram efetivas, decidi aplicar um teste z de hipóteses com um intervalo de confiança de 95% e o resuldo foi que sim, obtive uma melhora significativa no modelo. 

**Com o objetivo em mente, consegui construir um modelo de Machine Learning utilizando o algoritmo LightGBM e obter um recall de 71% e um AUC de 74.58%.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ferreiramar96/Analise_Risco_de_Credito_Nubank/main/Imagens/resultado_final.png" alt="imagem maneira relacionada ao projeto"height=320px >
</p>

A seguir, alguns pontos do projeto:
* Análise exploratória para entender os dados
* Modelagem dos dados
* Feature Engineering
* Codificação de Variáveis
* Escalonamento dos dados
* Treinamento de vários algoritmos
* Tunagem de Hiperparâmetros
* Testes Estatísticos
* Avaliação dos resultados e conclusão

Ao longo de todo o projeto, cada célula de código está explicada para uma fácil compreensão, acompanhado de um belo storytelling. Vocês também encontrarão algumas análises estatísticas, histogramas, matriz de correlação e toda a parte de pré-processamento dos dados, desde as análises até a avaliação dos modelos.

Neste projeto foi utilizado: Storytelling, Estatística, Série Temporal, Python, Machine Learning e Modelagem de Dados.


[Link para o projeto completo](https://github.com/ferreiramar96/Analise_Risco_de_Credito_Nubank/blob/main/Avalia%C3%A7%C3%A3o_de_Risco_Cr%C3%A9dito_Nubank.ipynb)

**Links para me acharem:**
* [Artigo desse projeto no Linkedin](https://www.linkedin.com/feed/update/urn:li:activity:7141405755013869568/)
* [LinkedIn](https://www.linkedin.com/in/felipeferreiratids/)
* [Instagram](https://www.instagram.com/ferreiramar96/)
* [Portfólio Completo](https://github.com/ferreiramar96/Data_Science)
