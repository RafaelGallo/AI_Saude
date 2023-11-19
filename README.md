# AI Saúde 

[![author](https://img.shields.io/badge/author-Rafael_Gallo-red.svg)](https://github.com/RafaelGallo?tab=repositories) 
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-374/) 
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) 
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-green.svg?style=flat)]([https://github.com/danielesantiago/Data-Science](https://github.com/RafaelGallo?tab=repositories))
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-374/) 
[![](https://img.shields.io/badge/Pandas-blue.svg)](https://pandas.pydata.org/) 
[![](https://img.shields.io/badge/Matplotlib-blue.svg)](https://matplotlib.org/)
[![](https://img.shields.io/badge/Seaborn-green.svg)](https://seaborn.pydata.org/)
[![](https://img.shields.io/badge/Matplotlib-orange.svg)](https://scikit-learn.org/stable/) 
[![](https://img.shields.io/badge/Numpy-white.svg)](https://numpy.org/)
[![](https://img.shields.io/badge/Tensorflow-orange.svg)](https://tensorflow.org/stable/)
[![](https://img.shields.io/badge/Keras-red.svg)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/Cuda-green.svg)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/GPU-green.svg)](https://scikit-learn.org/stable/)

![](https://github.com/RafaelGallo/AI_Saude_out/blob/main/imagem/4241961.jpg?raw=true)

# Descrição projeto
Este conjunto de dados é derivado da análise de características extraídas de imagens digitalizadas de aspirados com agulha fina (PAAF) de massas mamárias. As características fornecem informações detalhadas sobre os núcleos celulares presentes nas imagens, possibilitando uma análise aprofundada. O espaço tridimensional referido no contexto deste conjunto de dados é baseado no trabalho de KP Bennett e OL Mangasarian, intitulado "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets," publicado em Optimization Methods and Software em 1992 (vol. 1, pp. 23-34). Esse espaço tridimensional desempenha um papel fundamental na aplicação das técnicas de classificação utilizadas neste conjunto de dados.

## Informações dos Atributos

O conjunto de dados é composto por três categorias principais de informações:

- Número de Identificação
- Diagnóstico: Este atributo indica se a massa mamária é maligna (M) ou benigna (B).

## Diciónario dados

Dez Características de Valor Real para Cada Núcleo Celular: Cada uma dessas características contém informações significativas sobre os núcleos celulares encontrados nas imagens.

- a) Raio: Média das distâncias do centro aos pontos do perímetro.
- b) Textura: Desvio padrão dos valores da escala de cinza.
- c) Perímetro.
- d) Área.
- e) Suavidade: Variação local nos comprimentos do raio.
- f) Compacidade: Calculada como (perímetro ^ 2) / área - 1.0.
- g) Concavidade: Gravidade das porções côncavas do contorno.
- h) Pontos Côncavos: Número de porções côncavas do contorno.
- i) Simetria.
- j) Dimensão Fractal: Também conhecida como "aproximação da linha costeira."

## Distribuição de Classes

O conjunto de dados é composto por duas classes principais:

- 357 casos benignos. 212 casos malignos.

Essas informações fornecem uma visão geral abrangente deste conjunto de dados, permitindo que pesquisadores e profissionais realizem análises de classificação e detecção de câncer de mama com base em características celulares extraídas de imagens de PAAF.

# Objetivo e Problema
## Desenvolvimento de um Modelo de Machine Learning

A principal meta deste projeto é criar um modelo de aprendizado de máquina robusto e preciso que possa analisar os dados dessas imagens e fazer previsões precisas sobre a presença da doença. Para alcançar esse objetivo, serão aplicadas técnicas de processamento de imagens e algoritmos de aprendizado de máquina avançados. O modelo será treinado com base nas características dos núcleos celulares presentes nas imagens para realizar diagnósticos precisos e apoiar profissionais de saúde na tomada de decisões.

## Contribuição para a Compreensão da Doença

Este estudo não só busca criar um modelo de machine learning para prever a doença, mas também visa contribuir para uma compreensão mais ampla do câncer de mama. A análise das características celulares e a identificação de fatores-chave podem lançar luz sobre a progressão da doença, fatores de risco e potenciais tratamentos. Esses insights têm o potencial de impactar positivamente a prática clínica e a pesquisa médica relacionada ao câncer de mama. Em resumo, este projeto tem como objetivo central o desenvolvimento de um modelo de machine learning para a previsão de doenças, com ênfase na detecção de câncer de mama, ao mesmo tempo em que busca a extração de insights significativos para ampliar o conhecimento sobre a doença e suas características.

# Observação
Este projeto de machine learning aplicado à saúde não deve ser utilizado com o objetivo de simplesmente obter resultados. Em vez disso, é essencial enfatizar que a sua aplicação deve visar benefícios significativos e éticos, indo além da mera busca por resultados. A aplicação de machine learning na área de saúde requer uma abordagem responsável e cuidadosa, com foco na qualidade e na segurança dos resultados obtidos. O propósito fundamental não é apenas gerar resultados !

## Metodologia

**Aplicação machine learning**

A metodologia adotada neste projeto é alicerçada em uma abordagem multifacetada que tira proveito das últimas inovações em inteligência artificial. Começando com a coleta de dados de exames médicos e imagens de mamografias, nossa plataforma utiliza algoritmos de machine learning para realizar análises complexas. A partir dessas análises, desenvolvemos um sistema de deep learning capaz de identificar padrões sutis que muitas vezes passam despercebidos em avaliações tradicionais. A aplicação de deep learning permite que a IA detecte anormalidades, calcificações, nódulos e outros indicadores de potenciais tumores, ajudando os profissionais de saúde a fazer um diagnóstico mais preciso e, assim, melhorar as taxas de sobrevivência das pacientes.

## Aplicação no Mês de Outubro Rosa

O mês de Outubro Rosa é um período de destaque em nossa iniciativa. Durante este mês, intensificamos nossos esforços de conscientização e promoção do autocuidado e da detecção precoce do câncer de mama. Disponibilizamos acesso gratuito a nossa plataforma de análise de mamografias e encorajamos mulheres de todas as idades a fazerem exames regulares.
Nossa tecnologia não apenas auxilia na detecção, mas também na prevenção, uma vez que fornecemos informações e recursos valiosos sobre como manter a saúde mamária e reduzir os riscos. Estamos comprometidos em apoiar a luta contra o câncer de mama, fornecendo uma ferramenta eficaz e acessível para a detecção precoce, uma das principais armas na batalha contra essa doença. Em resumo, nosso projeto de inteligência artificial, que incorpora machine learning e deep learning, assume um papel crucial na identificação e conscientização do câncer de mama, especialmente durante o mês de Outubro Rosa. Acreditamos que, com o avanço da tecnologia e a conscientização pública, podemos fazer progressos significativos na detecção precoce e, finalmente, na erradicação dessa doença devastadora.

# Insights importante projeto 

Este relato abordará minuciosamente os insights mais relevantes extraídos da análise de dados. Em seguida, explorarei em detalhes a etapa crucial de engenharia de features e a aplicação do aprendizado de máquina.

**Análise exploratória de dados**

## Gráfico barra
Neste gráfico de barras, é claramente evidente que o número de casos de câncer benigno é menor do que o número de casos de câncer maligno. Essa representação visual nos fornece uma compreensão imediata da distribuição dos resultados. É fundamental notar que a diferença na prevalência de câncer benigno e maligno é um fator relevante, pois influencia diretamente as estratégias de diagnóstico e tratamento empregadas na área médica. A análise desses dados é fundamental para tomadas de decisão informadas e abordagens eficazes no cuidado de pacientes.

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*5moZB6jU6R3bB85PE7UDMQ.png)

## Gráfico media
A média de casos de câncer benigno se destaca, sendo maior do que a média de casos de câncer maligno. Isso indica que, em um conjunto de dados, a presença de casos de câncer benigno é mais comum do que a de câncer maligno. Essa disparidade na média entre os dois tipos de câncer tem implicações significativas em várias áreas, como estratégias de triagem e políticas de saúde. É importante considerar que a diferença na prevalência de câncer benigno e maligno pode influenciar a alocação de recursos e o desenvolvimento de abordagens terapêuticas. Compreender essa relação estatística entre os tipos de câncer é essencial para orientar decisões clínicas e estratégias de prevenção, proporcionando uma visão mais precisa do cenário de saúde em questão.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/09f87e09-f3ce-4cdf-9be1-0ee81c79b33e)

## Gráfico correlação entre os dados
Nesse gráfico, podemos observar a correlação entre os dados presentes na base de dados. Através dessa representação visual, conseguimos identificar e analisar as relações e associações entre as variáveis presentes nos dados. Essa análise de correlação é fundamental para compreender como as diferentes variáveis se relacionam entre si e como influenciam os resultados. A identificação de correlações é crucial em diversas áreas, como na pesquisa científica, na tomada de decisões de negócios e no campo da medicina. Ela permite a identificação de tendências e padrões que podem fornecer insights valiosos para a formulação de hipóteses, previsões e estratégias direcionadas. Portanto, a análise de correlação desempenha um papel importante na extração de conhecimento a partir dos dados.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/3494ee29-aed2-4ed3-9d6d-7851c1fff381)

## Gráfico boxplot
Neste gráfico, utilizamos um gráfico de boxplot como uma ferramenta valiosa para identificar possíveis outliers na variável-alvo. A detecção de outliers é um passo crítico na preparação dos dados para modelos de machine learning, uma vez que valores atípicos podem afetar significativamente o desempenho e a precisão desses modelos. Os outliers representam observações que estão significativamente afastadas do padrão geral dos dados. A identificação e o tratamento adequado de outliers são essenciais, pois podem levar a resultados distorcidos e predições imprecisas. Ao explorar o boxplot, podemos visualmente identificar valores que se afastam do intervalo interquartil e, assim, determinar se são candidatos a serem outliers. A remoção ou o tratamento cuidadoso de outliers é uma etapa importante na preparação de dados para modelagem de machine learning, contribuindo para um modelo mais robusto e preciso. Portanto, a análise de boxplot desempenha um papel fundamental na garantia da qualidade dos dados utilizados no processo de aprendizado de máquina.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/8c5d644e-f5b1-461e-950f-58d76bea7eb6)

## Gráfico subplots
Nesse gráfico, podemos claramente identificar a presença de outliers, que são valores atípicos que se destacam do padrão geral dos dados. A detecção e o tratamento de outliers são etapas essenciais na análise de dados, pois esses valores atípicos têm o potencial de distorcer as análises estatísticas e comprometer a precisão dos modelos de machine learning. Além disso, ao utilizar subplots juntos com essa análise, podemos visualizar a extensão dos problemas de outliers que afetam diversas partes do conjunto de dados. Os subplots permitem uma abordagem mais detalhada, possibilitando a identificação de valores atípicos em diferentes segmentos dos dados. Identificar e compreender a natureza desses valores atípicos é crucial para adotar estratégias adequadas de tratamento, como remoção, transformação ou imputação, a fim de garantir que o modelo de machine learning seja robusto e capaz de fazer previsões precisas. A gestão eficaz dos outliers não apenas aprimora a qualidade dos dados, mas também contribui para resultados mais confiáveis e representativos em análises estatísticas e modelagem. Portanto, a identificação e o tratamento de outliers são aspectos críticos em qualquer projeto de ciência de dados ou análise estatística, e o uso de subplots pode aprimorar a capacidade de identificar e entender a distribuição desses valores atípicos em todo o conjunto de dados.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/a35cea7a-52cb-40e8-8c0e-eff168699432)

**Pré-processamento**

# Pré-processamento
O Label Encoder é uma técnica de pré-processamento de dados essencial, especialmente quando se lida com a normalização de variáveis categóricas em projetos de machine learning. Variáveis categóricas representam categorias ou grupos, como “maçã”, “laranja” ou “banana”, em contraste com variáveis numéricas que expressam valores quantitativos. Dado que a maioria dos modelos de machine learning requer entradas numéricas, é crucial converter variáveis categóricas em formatos numéricos compreensíveis. O LabelEncoder é uma das abordagens mais comuns para atingir esse objetivo. O LabelEncoder realiza essa tarefa atribuindo a cada categoria em uma variável categórica um valor numérico exclusivo. Por exemplo, se você tem uma coluna chamada “Fruta” com valores como “Maçã”, “Laranja” e “Banana”, o LabelEncoder atribuirá valores numéricos, como 0, 1 e 2, respectivamente, a essas categorias. Essa codificação numérica permite que os modelos de machine learning compreendam e processem essas variáveis categóricas de maneira eficaz. No entanto, é importante notar que, ao usar o LabelEncoder, você deve estar ciente de que a atribuição de valores numéricos a categorias pode criar uma suposição de ordem que pode não ser apropriada para todos os conjuntos de dados. Portanto, em alguns casos, é necessário considerar técnicas adicionais, como a codificação one-hot, para evitar interpretações equivocadas e garantir uma modelagem precisa.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/35951b6e-6cdf-4510-95f8-b15ed6062643)

## Resultado normalização dados
Aqui, apresentamos o resultado da normalização, que é realizada por meio da aplicação do Label Encoder, transformando os dados em valores binários, ou seja, 0 e 1. 

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/d53a3571-74af-4fc4-a70a-63d10432d523)

**Machine learning**

## Modelo machine learning - XGBoost

XGBoost (Extreme Gradient Boosting) é uma implementação otimizada do algoritmo de gradient boosting que se destaca por sua eficiência e desempenho. Foi desenvolvido por Tianqi Chen como uma extensão da biblioteca Gradient Boosting Machine (GBM). O XGBoost é amplamente utilizado em competições de ciência de dados e aplicado em diversos problemas de aprendizado de máquina, como classificação, regressão e ranking. Ele se destaca por sua capacidade de lidar com grandes conjuntos de dados, alta velocidade de treinamento e melhorias em relação às implementações tradicionais de gradient boosting.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/222b881a-b327-4fc0-a5cd-913b594584ff)

## Feature
Aqui, as características mais importantes do modelo XGBoost desempenham um papel fundamental na compreensão do seu desempenho excepcional. O XGBoost sobressai ao destacar as features mais impactantes no processo de aprendizado, permitindo uma análise mais profunda e significativa. Por meio da identificação das features de maior relevância, é possível otimizar a modelagem e a tomada de decisões. Através dessa abordagem, o XGBoost proporciona uma vantagem competitiva ao destacar as características-chave que impulsionam o desempenho superior do modelo em relação a outros algoritmos de machine learning. Esse destaque nas features mais importantes do XGBoost é fundamental para a compreensão abrangente e aprimoramento contínuo do modelo.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/c0650a53-c8eb-4285-a80b-6783965c342c)

## Matriz de confusão

Nessa matriz de confusão do modelo XGBoost, podemos analisar o resultado das previsões em relação à ocorrência da doença. Ela é composta por quatro elementos:

- Verdadeiros Positivos (VP): Isso representa os casos em que o modelo previu corretamente a presença da doença, e essas previsões estavam corretas. No caso do modelo, houve 69 verdadeiros positivos.

- Verdadeiros Negativos (VN): Os verdadeiros negativos são os casos em que o modelo previu corretamente a ausência da doença, e essas previsões estavam corretas. Aqui, houve 40 verdadeiros negativos.

- Falsos Positivos (FP): Os falsos positivos ocorrem quando o modelo prevê erroneamente a presença da doença, mas a condição real é a ausência da doença. No caso do modelo, ocorreram 2 falsos positivos.

- Falsos Negativos (FN): Os falsos negativos ocorrem quando o modelo prevê erroneamente a ausência da doença, mas a condição real é a presença da doença aqui, ocorreram 3 falsos negativos.

A matriz de confusão é uma ferramenta fundamental na avaliação do desempenho de modelos de classificação, permitindo a análise de como o modelo lida com diferentes cenários de previsão. Com base nesses elementos, é possível calcular diversas métricas de avaliação, como a Precisão, o Recall e o F1-Score, que nos ajudam a entender o quão eficaz o modelo é na detecção da doença. É importante interpretar e usar esses resultados para ajustar e otimizar o modelo, caso necessário, para obter o melhor desempenho possível.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/26366501-b501-48ff-ad7a-aeb50da9f3e7)

## Plot matriz de confusão

Aqui, apresentamos o resultado da matriz de confusão na forma de um plot. A matriz de confusão é uma ferramenta crucial na avaliação de modelos de classificação, e o seu plot fornece uma representação visual dessa matriz, tornando a interpretação dos resultados mais acessível.

![image](https://github.com/RafaelGallo/AI_Saude_out/assets/44452165/28667e2b-981a-4178-86cd-6380af8aef93)

# Conclusão

Este projeto de inteligência artificial representa um marco no combate ao câncer de mama, unindo a vanguarda da tecnologia à causa do Outubro Rosa. Através da aplicação de machine learning e deep learning, estamos capacitando médicos e pacientes com uma ferramenta que pode salvar vidas ao permitir diagnósticos mais rápidos e precisos. À medida que celebramos o Outubro Rosa, nosso compromisso com a conscientização e a detecção precoce do câncer de mama é mais forte do que nunca. Nosso objetivo é tornar a saúde mamária acessível a todos e capacitar as mulheres a cuidar de sua saúde de maneira proativa. Juntos, podemos trabalhar para reduzir o impacto devastador do câncer de mama na sociedade. Continuaremos a aprimorar nossa tecnologia e a expandir nossos esforços para garantir que a detecção precoce e a conscientização sobre o câncer de mama se tornem cada vez mais eficazes, proporcionando esperança e melhores resultados para todas as mulheres.

# Dedicação
Gostaria de expressar minha gratidão e dedicação a minha querida amiga, Karoline Veronese Riveira, através deste artigo. Karoline tem sido uma presença constante e inspiradora em minha vida, e é com grande alegria que compartilho este trabalho em sua homenagem. Sua amizade tem sido uma fonte inesgotável de apoio, incentivo e alegria, tornando esta dedicação um gesto simbólico de apreço por tudo o que ela representa para mim.
