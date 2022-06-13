# Projeto final: introdução ao aprendizado de máquinas
Este repositório contém informações a respeito do projeto desenvolvido na disciplina MAC0460/5832 de introdução a ao aprendizado de máquinas. 

Neste projeto, nos propomos a tentar prever o resultado das partidas com base em informações geradas ao final de cada uma delas. O conjunto de dados está disponível no [Kaggle](https://www.kaggle.com/datasets/kdanielive/lol-partchallenger-1087) e possuí mais de 10 mil diferentes partidas contendo mais de 1500 features que representam informações sobre cada partida como duração da partida, número de abates de cada equipe, número de monstros abatidos, número de torres destruídas, resultado, _etc._.

# Sobre o conjunto de dados
O conjunto de dados não estará disponível neste repositório (talvez na versão final). Assim, para executar as análises disponíveis será necessário baixar e extrair o conjunto de dados para o diretório `DATA/`.

Devido a grande quantidade de features no conjunto escolhido (raw), apenas as features selecionadas (ver tabela abaixo) foram utilizadas.

# Configurando o workspace
A princípio qualquer versão do Python>=3.8.10 deve ser suficiente. Além disso, as seguintes bibliotecas foram utilizadas (em suas últimas versões):
- Pandas
- Numpy
- Matplotlib
- sklearn

Por fins de praticidade, o gerenciamento de dependências pode ser feito através do `pipenv`; as bibliotecas estão listadas no `Pipfile`. Para instalar o workspace a partir do `Pipfile` basta executar
```
pipenv install
```
na raíz do repositório. Mais detalhes de como usar o pipenv estão disponíveis [aqui](https://pipenv.pypa.io/en/latest/).