<h1>Projeto de Predição da Necessidade de Leitos de UTI para COVID-19 no Hospital Sírio-Libanês</h1>
Este é um projeto de Data Science que utiliza algoritmos de classificação para prever a necessidade de internação em UTI de pacientes com COVID-19, com base em dados clínicos e demográficos. A análise exploratória e visualização dos dados foram realizadas para entender melhor os dados e extrair conhecimento deles.

Dados
Os dados foram fornecidos pelo Hospital Sírio-Libanês e contêm informações sobre pacientes admitidos no hospital com COVID-19. Os dados, anonimizados, incluem informações clínicas e demográficas, como idade, sexo, resultados de exames de sangue, etc. e podem ser encontrados no link https://www.kaggle.com/S%C3%ADrio-Libanes/covid19..

Pré-processamento dos dados
Antes de treinar os modelos, os dados foram pré-processados para garantir a qualidade e a coerência dos dados. O pré-processamento incluiu tratamento de dados ausentes, codificação de variáveis categóricas, normalização de dados numéricos, etc.

Modelagem
Vários modelos de classificação foram treinados e comparados usando validação cruzada e métricas de desempenho, como acurácia, precisão, recall, F1-score, etc. Os modelos testados incluem Decision Tree, Random Forest, Logistic Regression, K-Nearest Neighbors, Support Vector Machines e Gradient Boosting.

Resultados
Tivemos melhor desempenho com o modelo RandomForestClassifier(), ultrapassando 81% de acurácia em relação à classificação de pacientes que foram ou não para a UTI, sem nenhum tipo de otimização no modelo.

Componentes personalizados
Além dos componentes padrão do spaCy, foram adicionados componentes personalizados ao pipeline do spaCy para realizar o pré-processamento dos dados e a análise exploratória dos dados.

Dependências
As seguintes bibliotecas Python e ferramentas foram usadas neste projeto:

Python
Jupyter Notebook
Pandas, Numpy
Matplotlib, Seaborn
Modelos de Machine Learning: LogisticRegression, DecisionTreeClassifier, SVC, RandomForestClassifier, KNeighborsClassifier
Git e Github
