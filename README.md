# azure-regression-training
Treino de regressão utilizando Azure ML. Exercício DIO.
Utilizando o Azure Machine Learning Studio, criei um trabalho automatizado de machine Learning, utilizando como base as seguintes configurações:
 - None: mlazure_bikerental
 - Tarefa do tipo Regressão
 - Métrica primária : Erro de quadrado de média de raiz normalizado
 - Modelos permitidos : RandomForest e LightGBM
 - Tempo de treinamento 15 minutos (0.25 horas)
 - Validação: Divisão de validação de treinamento
 -  Número máximo de iterações simultâneas : 3
Os dados utilizados neste treino são de origem da WEB (https://aka.ms/bike-rentals).
O processamento do trabalho de treinamento levou 25 minutos. Após sua conclusão, selecionei o melhor modelo apontado no treinamento (VotingEsenble), e o implantei no formato Serviço Web (após a devida validação dos
campos em Métricas).
ID do serviço - previsao-aluguel-bike
Tipo de computação - instância de contêiner.
Os artefatos gerados estão disponíveis neste repositório.
