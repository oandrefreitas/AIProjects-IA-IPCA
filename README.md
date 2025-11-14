//******************************PORTUGUÊS******************************//

# AIProjects-IA-IPCA

Repositório com os trabalhos práticos da unidade curricular de Inteligência Artificial (IA), focados em planeamento/otimização com restrições e em técnicas de mineração de dados. Inclui um modelo de calendarização de projeto baseado em programação por restrições e vários notebooks em Python para classificação supervisionada, clustering e extração de regras de associação.

## Funcionalidades principais

* **TP1 – Planeamento de Projeto com Restrições**
  * Modelo de calendarização de tarefas usando programação por restrições em Python (`python-constraint`).
  * Cálculo de domínios de início/fim para cada tarefa com base em durações e precedências.
  * Geração de múltiplas soluções viáveis e seleção da solução com menor makespan.
  * Apoio à visualização da calendarização e análise do impacto de alterações no plano do projeto.
  * Utilização de diferentes conjuntos de dados (`P01 DataSet-4/8/10/30.txt`) para testar cenários.

* **TP2 – Mineração de Dados e Aprendizagem Automática**
  * **Classificação automática de imóveis**:
    * Pré-processamento e engenharia de atributos (criação de categorias de preço, novos atributos derivados, etc.).
    * Treino e avaliação de modelos como *Random Forest* e *K-Nearest Neighbors* (KNN).
    * Utilização de técnicas de *bagging* e *k-fold cross-validation* para comparação de desempenho.
    * Análise de métricas de classificação e comparação entre modelos.

  * **Clustering/Agrupamento de dados**:
    * Normalização e seleção de atributos relevantes.
    * Aplicação de algoritmos de clustering (ex.: *K-Means*).
    * Análise e interpretação dos clusters obtidos.
    * Comparação gráfica e estatística dos grupos formados.

  * **Regras de associação com Apriori**:
    * Discretização de atributos contínuos para preparação do dataset.
    * Geração de conjuntos frequentes e regras de associação com o algoritmo **Apriori**.
    * Análise de suporte, confiança e lift.
    * Foco em regras relacionadas com atributos específicos (ex.: área do imóvel) e interpretação dos padrões descobertos.

//******************************ENGLISH******************************//

# AIProjects-IA-IPCA

Repository containing the practical assignments for the Artificial Intelligence course, focused on constraint-based planning/optimisation and data mining techniques. It includes a project scheduling model in Python using constraint programming and several Jupyter notebooks for supervised classification, clustering and association rule mining.

## Main Features

* **TP1 – Constraint-Based Project Scheduling**
  * Project scheduling model using constraint programming in Python (`python-constraint`).
  * Computation of start/end time domains for each task based on durations and precedence constraints.
  * Generation of multiple feasible schedules and selection of the solution with the lowest makespan.
  * Support for visualising the schedule and analysing the impact of changes to the project plan.
  * Use of different datasets (`P01 DataSet-4/8/10/30.txt`) to test alternative scenarios.

* **TP2 – Data Mining and Machine Learning**
  * **Automatic property classification**:
    * Data preprocessing and feature engineering (price categories, derived attributes, etc.).
    * Training and evaluation of models such as *Random Forest* and *K-Nearest Neighbors* (KNN).
    * Use of *bagging* and *k-fold cross-validation* to compare model performance.
    * Analysis of classification metrics and comparison between different models.

  * **Clustering of data**:
    * Normalisation and selection of relevant features.
    * Application of clustering algorithms (e.g. *K-Means*).
    * Analysis and interpretation of the resulting clusters.
    * Graphical and statistical comparison of the identified groups.

  * **Association rules with Apriori**:
    * Discretisation of continuous attributes to prepare the dataset.
    * Generation of frequent itemsets and association rules using the **Apriori** algorithm.
    * Analysis of support, confidence and lift.
    * Focus on rules related to specific attributes (e.g. property area) and interpretation of discovered patterns.
