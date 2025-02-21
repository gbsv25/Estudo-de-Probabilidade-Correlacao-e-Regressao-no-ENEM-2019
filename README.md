## **Análises Estatísticas e Modelagem Preditiva com Dados do ENEM**

**Breve Descrição sobre os dois arquivos de código**

Este projeto combina duas análises estatísticas distintas aplicadas aos dados do ENEM 2019:

Correlação e Regressão Linear: Examina a relação entre as notas dos alunos em diferentes áreas do conhecimento e constrói um modelo de regressão linear para prever a nota final com base na nota de redação.

Métricas de Probabilidade: Calcula probabilidades de eventos específicos dentro do conjunto de dados, aplica distribuições discretas para modelar eventos estatísticos e realiza testes de normalidade para avaliar a distribuição dos dados.

O objetivo é fornecer insights estatísticos sobre o desempenho dos estudantes e explorar técnicas de modelagem preditiva para auxiliar na tomada de decisões educacionais.

**Problema e Objetivos**

1. Correlação e Regressão Linear

Problema: 

- Determinar se a nota de redação pode ser utilizada para prever a média final dos alunos de um colégio específico.

Objetivos: 
- Calcular a matriz de correlação entre as diferentes notas.

- Criar um modelo de regressão linear para prever a nota final baseada na nota de redação.

- Avaliar a normalidade dos resíduos e a adequação do modelo.

2. Métricas de Probabilidade

Problema: 
- Modelar probabilidades de eventos dentro do conjunto de dados do ENEM 2019 e avaliar a distribuição dos dados.

Objetivos:

- Calcular a probabilidade de selecionar um estudante com características específicas.

- Aplicar distribuições probabilísticas (Binomial, Geométrica e Poisson) para modelar eventos discretos.

- Avaliar a normalidade dos dados por meio de testes estatísticos.

Metodologia

1. Correlação e Regressão Linear

Coleta de Dados: 

-  O dataset foi obtido do ENEM 2019, tratado previamente (como demosntrado no arquivo "tratamento dos dados ENEM 2019 neste perfil - https://github.com/gbsv25/Analise-Estatistica-dos-Dados-do-ENEM-2019--Estado-de-Sao-Paulo/blob/3445afb5d7e0ad65e4481f310bbced68a905008d/tratamento_dados_enem_2019.ipynb) e armazenado no Google Drive.

Limpeza e Preparação:

- Selecionamos um colégio específico para análise.

- Calculamos a média final dos alunos com base em suas notas nas disciplinas avaliadas.

2. Análise Exploratória de Dados (EDA):

Construção de gráficos de dispersão e matriz de correlação para identificar padrões entre as variáveis.

## Modelagem:

Aplicação de regressão linear simples para prever a nota final com base na nota de redação.

Validação:

Análise dos resíduos do modelo e realização de testes de normalidade.

1. Métricas de Probabilidade

Probabilidades:

Cálculo da probabilidade de selecionar um estudante de um município específico.

Probabilidade de ocorrência de eventos mutuamente exclusivos e interseccionais.

Distribuições Discretas:

Aplicação das distribuições Binomial, Geométrica e de Poisson para modelar eventos.

Testes de Normalidade:

Utilização de histogramas e QQ-Plots para avaliar a distribuição das notas.

Aplicação do Teste de Shapiro-Wilk para verificar se as notas seguem uma distribuição normal.

Uso do Teste de Kolmogorov-Smirnov (Lilliefors) para confirmar a aderência dos dados à distribuição normal.

## Resultados

1. Correlação e Regressão Linear

A matriz de correlação revelou relações significativas entre as notas das diferentes áreas do conhecimento.

O modelo de regressão linear indicou que a nota de redação é um bom preditor da nota final dos alunos.

A análise dos resíduos sugeriu que o modelo atende aos pressupostos estatísticos para regressão linear.

2. Métricas de Probabilidade

A probabilidade de selecionar um estudante de Guarulhos foi de 3,13%, enquanto para Bauru foi de 0,83%.

A distribuição binomial mostrou que a chance de selecionar 4 mulheres em uma amostra de 10 foi 13,01%.

A distribuição geométrica indicou que a probabilidade de encontrar a primeira mulher na quarta tentativa foi 4,29%.

A distribuição de Poisson revelou que a chance de exatamente 90 alunos terminarem a prova em 2 horas foi 2,5%.

Os testes de normalidade indicaram que algumas variáveis seguem uma distribuição normal, enquanto outras apresentam desvios significativos, conforme os testes de Shapiro-Wilk e Kolmogorov-Smirnov.

## Conclusão

Os resultados sugerem que a nota de redação pode ser usada como um indicador do desempenho geral dos alunos. Além disso, as análises probabilísticas fornecem insights sobre a distribuição dos estudantes e a ocorrência de eventos dentro do conjunto de dados. Os testes de normalidade mostraram quais variáveis seguem uma distribuição normal, impactando a escolha de métodos estatísticos adequados para análise posterior. Essas informações podem ser úteis para educadores e formuladores de políticas educacionais.



**Ferramentas e Tecnologias**

Linguagens de Programação: Python

Bibliotecas Utilizadas: Pandas, NumPy (Manipulação de dados), Seaborn, Matplotlib, Plotly (Visualização de dados), Scipy e Statsmodels (Estatística e modelagem)

Plataformas: Google Colab (Ambiente de execução)
