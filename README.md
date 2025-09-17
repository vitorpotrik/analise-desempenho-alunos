#Análise de Desempenho de Alunos em Matemática
Este projeto realiza uma análise estatística e visual do desempenho de alunos em matemática, segmentados por turma. Utilizando um conjunto de dados com notas e informações socioeconômicas, o notebook explora, calcula e visualiza diversas métricas para extrair insights sobre o rendimento acadêmico.

#📊 Sobre o Projeto
O objetivo principal é fornecer uma análise detalhada do desempenho dos alunos, permitindo a identificação de padrões e a classificação das turmas com base na distribuição de suas notas. O projeto utiliza a biblioteca pandas para manipulação dos dados, matplotlib e seaborn para a criação de gráficos.

#As principais análises realizadas são:

Estatísticas Descritivas: Cálculo de métricas como média, mediana, desvio padrão, variância, e quartis para cada turma.

Distribuição de Frequência: Criação de tabelas que mostram a distribuição das notas dos alunos em intervalos pré-definidos.

Classificação de Desempenho: As turmas são classificadas em categorias como "Homogêneo e Suficiente", "Homogêneo e Insuficiente", "Polarizado" ou "Heterogêneo" com base na concentração das notas.

Visualização de Dados: Geração de histogramas, boxplots e gráficos de barras para comparar o desempenho entre as turmas de forma visual.

Análises Adicionais: Análise comparativa do desempenho com base no gênero e no acesso à internet dos alunos.

#📁 Estrutura do Projeto
analise_alunos.ipynb: O notebook Jupyter contendo todo o código para a análise, desde a leitura dos dados até a geração dos gráficos e conclusões.

notas_alunos.xlsx: O arquivo de dados contendo as informações dos alunos.

#O Conjunto de Dados
O arquivo notas_alunos.xlsx possui a seguinte estrutura:

#Coluna	Descrição	Tipo de Dado
Turma	A turma à qual o aluno pertence.	Categórico
Nota_Matematica	A nota do aluno na disciplina.	Numérico
Acesso_Internet	Se o aluno possui acesso à internet.	Categórico
Genero	O gênero do aluno.	Categórico

#Exportar para as Planilhas
🛠️ Tecnologias Utilizadas
Python 3

#Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn
