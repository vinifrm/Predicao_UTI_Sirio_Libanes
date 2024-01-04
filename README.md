![projeto sirio](https://user-images.githubusercontent.com/44147318/235558123-6bd2c302-1262-4237-8099-2e1724a4686a.png)
<h1>Projeto de Predição da Necessidade de Leitos de UTI para COVID-19 no Hospital Sírio-Libanês</h1>
Este é um projeto de Data Science que utiliza algoritmos de classificação para prever a necessidade de internação em UTI de pacientes com COVID-19, com base em dados clínicos e demográficos. A análise exploratória e visualização dos dados foram realizadas para entender melhor os dados e extrair conhecimento deles.

<h3>Dados</h3>
Os dados foram fornecidos pelo Hospital Sírio-Libanês e contêm informações sobre pacientes admitidos no hospital com COVID-19. Os dados, anonimizados, incluem informações clínicas e demográficas, como idade, sexo, resultados de exames de sangue, etc. e podem ser encontrados no link https://www.kaggle.com/S%C3%ADrio-Libanes/covid19..

<h3>Pré-processamento dos dados</h3>
Antes de treinar os modelos, os dados foram pré-processados para garantir a qualidade e a coerência dos dados. O pré-processamento incluiu tratamento de dados ausentes, codificação de variáveis categóricas, normalização de dados numéricos, etc.

<h3>Modelagem</h3>
Vários modelos de classificação foram treinados e comparados usando validação cruzada e métricas de desempenho, como acurácia, precisão, recall, F1-score, etc. Os modelos testados incluem Decision Tree, Random Forest, Logistic Regression, K-Nearest Neighbors e SVC.

<h3>Resultados</h3>
Tivemos melhor desempenho com o modelo RandomForestClassifier(), ultrapassando 81% de acurácia em relação à classificação de pacientes que foram ou não para a UTI, sem nenhum tipo de otimização no modelo.

<h3>Dependências</h3>
As seguintes bibliotecas Python e ferramentas foram usadas neste projeto:

<ul>
  <li>Python</li>
  <li>Jupyter Notebook</li>
  <li>Pandas, Numpy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Modelos de Machine Learning: LogisticRegression, DecisionTreeClassifier, SVC, RandomForestClassifier, KNeighborsClassifier</li>
  <li>Git e Github</li>
</ul>
