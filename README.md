# MVP_Analise_de_dados_e_boas_praticas

### Introdução

O presente trabalho é um pré-requisito da disciplina Análise de Dados e Boas Práticas da pós graduação em Ciência de Dados e Analytics da PUC-Rio.

Nele é feita a análise do dataset AI4I 2020 Predictive Maintenance e são aplicados os conceitos aprendidos nas disciplinas do curso, como por exemplo, Análise Exploratória, Pré-processamento de Dados e Visualização de Informação.

O conjunto de dados de Manutenção Preditiva AI4I 2020 é um conjunto de dados sintético que reflete dados reais de manutenção preditiva encontrados na indústria.

### Estrutura do trabalho

O trabalho está dividido em tópicos, conforme a seguir:

1. Definição do problema: Este tópico apresenta o escopo do projeto, abordando o uso do dataset AI4I 2020 Predictive Maintenance. O objetivo é analisar e prever falhas em máquinas industriais, identificando padrões que sinalizem a ocorrência de machine_failure por meio de variáveis contínuas e categóricas.

2. Coleta dos Dados: Detalha o processo de aquisição e carregamento do dataset, utilizando o Google Colab e Python. As bibliotecas principais empregadas são Pandas, NumPy, Matplotlib, Seaborn e scikit-learn.

3. Análise de Dados: Nessa etapa é feita a Análise Exploratória (EDA) do dataset. Visa compreender a distribuição, relações e características das variáveis, utilizando estatísticas descritivas e diversas visualizações gráficas (gráficos de barras, boxplots, histogramas e mapas de calor) para verificar hipóteses e obter insights iniciais.

4. Pré Processamento de Dados: Descreve as etapas essenciais para preparar os dados para a modelagem. Inclui técnicas como normalização, padronização, seleção de características (via Random Forest), redução de dimensionalidade (PCA) e criação de novas características (Feature Engineering), garantindo a otimização para algoritmos de aprendizado de máquina.

5. Conclusão: Apresenta as principais descobertas da análise e pré-processamento. Destaca a importância de compreender a estrutura dos dados, a natureza desbalanceada do dataset, as correlações identificadas e a eficácia das visualizações. Reafirma a relevância das técnicas de normalização e padronização para o aprendizado de máquina, e valida as hipóteses levantadas com base nas análises gráficas.

### Hipóteses de Estudo

Foram levantadas as seguintes hipóteses que espera-se sejam provadas com a análise dos dados:

a) Máquinas com maior desgaste da ferramenta apresentam maior probabilidade de falha?

b) A combinação de alta temperatura do processo e alto torque está associada a um aumento nas falhas da máquina?

c) O tipo de produto fabricado influencia na taxa de falhas da máquina?

d) A variável velocidade rotacional (rpm) tem uma relação não linear com a falha?

e) A presença de falhas específicas como falha da ferramenta ou sobrecarga do sistema pode antecipar a ocorrência da falha geral da máquina?

### Dados Complementares

Link para o dataset utilizado: https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

Link para o notebook no Google Colab: https://colab.research.google.com/drive/1JbLo2yzNa9sPSDmrAYdFXoHCVMW7x6XW#scrollTo=msREpXL2D3xE.

Uma cópia do dataset (ai4i2020), em formato csv, encontra-se anexado a este repositório.
