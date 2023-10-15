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

## Introdução

Este projeto de inteligência artificial representa um avanço notável na área da saúde, incorporando tecnologias de ponta, como machine learning, análise de dados e deep learning, para a detecção precoce e precisa do câncer de mama. Com a crescente importância da conscientização sobre o câncer de mama, este projeto assume um papel central no mês de Outubro Rosa, um período dedicado à sensibilização e à educação sobre essa doença que afeta milhões de mulheres em todo o mundo.

## Observação
Esse projeto inteligência artificial aplicando machine learning, análise de dados, depp learning para intentificação câncer de mama este projeto dedicado ao mês Outubro rosa. 

## Metodologia

**Aplicação machine learning**

A metodologia adotada neste projeto é alicerçada em uma abordagem multifacetada que tira proveito das últimas inovações em inteligência artificial. Começando com a coleta de dados de exames médicos e imagens de mamografias, nossa plataforma utiliza algoritmos de machine learning para realizar análises complexas. A partir dessas análises, desenvolvemos um sistema de deep learning capaz de identificar padrões sutis que muitas vezes passam despercebidos em avaliações tradicionais. A aplicação de deep learning permite que a IA detecte anormalidades, calcificações, nódulos e outros indicadores de potenciais tumores, ajudando os profissionais de saúde a fazer um diagnóstico mais preciso e, assim, melhorar as taxas de sobrevivência das pacientes.

**Aplicações deep learning**

## Redes Neurais Convolucionais

Redes Neurais Convolucionais (CNNs, sigla em inglês para Convolutional Neural Networks) são um tipo especializado de rede neural artificial projetado para processar dados que têm uma estrutura de grade, como imagens. Elas são amplamente utilizadas em tarefas de visão computacional, como classificação de imagens, detecção de objetos, segmentação de imagens e muitas outras aplicações relacionadas a processamento de imagens e vídeos. As CNNs são altamente eficazes na extração de características relevantes de imagens e na redução da dimensionalidade dos dados, tornando-as ideais para tarefas de reconhecimento de padrões em imagens. Elas incluem camadas convolucionais e camadas de pooling que operam em dados de entrada em grade, além de camadas completamente conectadas para a classificação final.

As redes neurais convolucionais (CNNs) são particularmente eficazes na análise de imagens e são capazes de identificar padrões complexos que são essenciais para a detecção de anomalias nas mamografias. As CNNs, treinadas em vastos conjuntos de dados, podem distinguir entre tecido mamário normal e potenciais tumores, fornecendo uma análise precisa e automatizada. O algoritmo é constantemente refinado à medida que novos dados são incorporados, garantindo uma melhoria contínua na precisão.

**Arquitetura DenseNet121**

![img1](https://github.com/RafaelGallo/Coursera_IA_medicina/assets/44452165/09a36fcc-68c2-4157-8aaf-d5bd3fead1eb)

DenseNet-121, ou Densely Connected Convolutional Networks 121, é uma arquitetura de rede neural convolucional (CNN) que faz parte da família de modelos DenseNet. 
A principal característica que distingue as redes DenseNet de outras arquiteturas é a conexão densa (dense connection) entre as camadas. Em redes convencionais, como as ResNet, as ativações de uma camada são somadas às ativações da camada seguinte. No entanto, nas redes DenseNet, as ativações de todas as camadas anteriores são concatenadas em vez de somadas. Isso cria um fluxo de informações direto e denso em toda a rede, permitindo que as camadas mais profundas acessem informações das camadas mais rasas, o que ajuda a combater o problema do desvanecimento do gradiente e facilita o treinamento de redes profundas. O número "121" em DenseNet-121 refere-se à profundidade da rede. Nesse caso, a arquitetura consiste em 121 camadas convolucionais. O DenseNet-121 foi projetado para várias tarefas de visão computacional, como classificação de imagens, detecção de objetos e segmentação de imagens. Essas redes são amplamente utilizadas em tarefas de aprendizado profundo de visão, como classificação de imagens em conjuntos de dados como o ImageNet, devido à sua eficácia em aprender representações de alto nível de imagens. Além disso, elas têm a vantagem de serem altamente eficientes em termos de uso de parâmetros, o que as torna adequadas para implantações em recursos computacionais limitados.

**Res50Unet**

A designação "Res50Unet" não é um modelo de rede neural convolucional (CNN) amplamente reconhecido ou uma arquitetura específica de rede neural. No entanto, podemos dividir o nome em duas partes.

- Res50: A parte "Res50" provavelmente se refere a uma rede neural que utiliza a arquitetura ResNet-50. ResNet (Redes Residuais) é uma famosa arquitetura de rede neural convolucional que introduz conexões residuais entre camadas, permitindo que informações fluam diretamente de camadas anteriores para camadas posteriores. O número "50" geralmente indica a profundidade da ResNet, significando que a arquitetura ResNet-50 possui 50 camadas.

- Unet: "Unet" é uma arquitetura de rede neural convolucional projetada para segmentação de imagens. Ela é frequentemente usada em tarefas de segmentação semântica, onde o objetivo é classificar cada pixel de uma imagem em categorias específicas. A arquitetura Unet é conhecida por sua capacidade de capturar detalhes finos e preservar a resolução espacial da imagem.

Portanto, "Res50Unet" pode ser uma referência a uma arquitetura de rede que combina a arquitetura ResNet-50 com a estrutura da Unet, talvez com o objetivo de aproveitar os benefícios das conexões residuais da ResNet na tarefa de segmentação de imagens.


## Aplicação no Mês de Outubro Rosa

O mês de Outubro Rosa é um período de destaque em nossa iniciativa. Durante este mês, intensificamos nossos esforços de conscientização e promoção do autocuidado e da detecção precoce do câncer de mama. Disponibilizamos acesso gratuito a nossa plataforma de análise de mamografias e encorajamos mulheres de todas as idades a fazerem exames regulares.
Nossa tecnologia não apenas auxilia na detecção, mas também na prevenção, uma vez que fornecemos informações e recursos valiosos sobre como manter a saúde mamária e reduzir os riscos. Estamos comprometidos em apoiar a luta contra o câncer de mama, fornecendo uma ferramenta eficaz e acessível para a detecção precoce, uma das principais armas na batalha contra essa doença. Em resumo, nosso projeto de inteligência artificial, que incorpora machine learning e deep learning, assume um papel crucial na identificação e conscientização do câncer de mama, especialmente durante o mês de Outubro Rosa. Acreditamos que, com o avanço da tecnologia e a conscientização pública, podemos fazer progressos significativos na detecção precoce e, finalmente, na erradicação dessa doença devastadora.

## Conclusão

Este projeto de inteligência artificial representa um marco no combate ao câncer de mama, unindo a vanguarda da tecnologia à causa do Outubro Rosa. Através da aplicação de machine learning e deep learning, estamos capacitando médicos e pacientes com uma ferramenta que pode salvar vidas ao permitir diagnósticos mais rápidos e precisos. À medida que celebramos o Outubro Rosa, nosso compromisso com a conscientização e a detecção precoce do câncer de mama é mais forte do que nunca. Nosso objetivo é tornar a saúde mamária acessível a todos e capacitar as mulheres a cuidar de sua saúde de maneira proativa. Juntos, podemos trabalhar para reduzir o impacto devastador do câncer de mama na sociedade. Continuaremos a aprimorar nossa tecnologia e a expandir nossos esforços para garantir que a detecção precoce e a conscientização sobre o câncer de mama se tornem cada vez mais eficazes, proporcionando esperança e melhores resultados para todas as mulheres.
