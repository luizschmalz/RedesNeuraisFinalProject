Projeto Final da Disciplina de Redes Neurais, grupo:
-Luiz Eduardo Schmalz
-Henrique Melo
-Pedro Calheiros
-Matheus Braga

Tratamento de Dados e Redes Neurais
Este repositório contém scripts para tratamento de dados e implementações de quatro modelos de redes neurais: MLP, Random Forest, Gradient Boosting e KAN.

Conjunto de Dados
O conjunto de dados utilizado neste projeto é uma base de dados de classificação binária de satisfação em voos de uma empresa aérea. Cada entrada no conjunto de dados representa a satisfação de um cliente em um voo, categorizada como 'satisfeito' ou 'neutro ou insatisfeito'. 

Modelos
MLP (Multi-Layer Perceptron)
O MLP é uma rede neural feedforward clássica que consiste em múltiplas camadas de neurônios totalmente conectados. Ele é eficaz para uma variedade de problemas de classificação e regressão, funcionando bem com dados que possuem relações não lineares complexas.

Random Forest
O Random Forest é um modelo de ensemble baseado em árvores de decisão. Ele funciona criando múltiplas árvores de decisão durante o treinamento e saída da classe que é o modo das classes de saída (classificação) ou média das previsões (regressão) das árvores individuais. Ele é robusto contra overfitting e pode lidar com datasets grandes e complexos.

Gradient Boosting
O Gradient Boosting é uma técnica de machine learning de ensemble que cria um modelo preditivo forte a partir de vários modelos fracos, geralmente árvores de decisão. Ele otimiza a função de perda agregando árvores sequencialmente, onde cada nova árvore corrige os erros do modelo anterior.

KAN 
Redes de Kolmogorov-Arnold (KANs) são uma proposta de arquitetura de rede neural inspirada no teorema de representação de Kolmogorov-Arnold. Essa abordagem é considerada uma alternativa promissora às Perceptrons de Múltiplas Camadas (MLPs) usadas em modelos de aprendizado profundo.

Resultados
As métricas escolhidas para realizar a comparação de modelos são majoritariamente o valor KS de cada modelo, para chegar nesse valor temos também que ter uma curva ROC para cada modelo, além dessas métricas, em todos casos são printados as acurácias, para poder ter noção de qual modelo está se comportando melhor com diferentes hiperparâmetros.
