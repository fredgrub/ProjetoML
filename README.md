# Projeto final: introdução ao aprendizado de máquinas
Este repositório contém informações a respeito do projeto desenvolvido na disciplina MAC0460/5832 de introdução a ao aprendizado de máquinas. 

Neste projeto, nos propomos a tentar prever o resultado das partidas com base em informações geradas ao final de cada uma delas. O conjunto de dados está disponível no [Kaggle](https://www.kaggle.com/datasets/kdanielive/lol-partchallenger-1087) e possuí mais de 15 mil partidas contendo mais de 1500 features que representam informações sobre cada partida como duração da partida, número de abates de cada equipe, número de monstros abatidos, número de torres destruídas, resultado, _etc._.

# Sobre o conjunto de dados
O conjunto de dados não estará disponível neste repositório (talvez na versão final). Assim, para executar as análises disponíveis será necessário baixar e extrair o conjunto de dados para o diretório `DATA/`.

Devido a grande quantidade de features no conjunto escolhido (*raw*), foi necessário construir um novo conjunto de dados baseado no *raw*. O processo de extração das features está documentado no notebook `exploration.ipynb`. O conjunto final contém 35 features que descrevem informações de cada uma das mais de 15000 partidas.