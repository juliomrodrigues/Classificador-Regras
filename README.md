# Classificador-Regras
Treinando um modelo de classificação por regras e aplicando numa base de dados.

#### Treinando um modelo de classificação por regras e aplicando em uma base de dados para fazer previsões das classes dos registros(Base de Dados - Censo de 1994 - EUA).
#### Objetivo: Prever se um americano possui renda anual <= ou > 50 mil dólares por ano.

### Resultados - Validação Cruzada - StratifiedKFold
**Precisão** | **Pré-Processamentos** | **Desvio Padrão**
 | :------: | :------: | :------: |
 | LabelEncoder | 
 |  | 
 | LabelEncoder + StandardScaler |
 | OneHotEncoder + StandardScaler |
 | LabelEnconder + OneHotEncoder + StandardScaler |

### Matriz de Confusão(Média de todas as 10 execuções):
### Matriz de Confusão (Média):
x | **0** | **1**
| :------: | :------: | :------: |
0 |  | 
1 |  | 

A Matriz na tabela acima é formada pela média de todas as matrizes geradas ao longo de 10 execuções usando pré-processamentos .

A diagonal principal (em negrito) destaca os registros classificados corretamente.

### Bibliotecas usadas:
- Pandas
- Sklearn
- Numpy

### Técnicas de Pré-Processamento e Tratamento dos dados usada:
- LabelEnconder;
- OneHotEncoder;
- StandardScaler;

### Ferramentas Usadas:
- Anaconda
- Spyder

### Linguagem:
- Python

### Fonte da Base de Dados: 
- Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

### Como usar:
- Basta fazer o download do código fonte e da base de dados. Para executar o código por partes(células) e testar diferentes possibilidades de pré-processamento, recomendo uma IDE como Spyder ou o Jupyter. (Támbem é necessário ter o Python instalado no seu computador)

#### Outros Classificadores:
- [Naive Bayes](https://github.com/juliomrodrigues/Classificador-Naive-Bayes)
- [Árvore de Decisão](https://github.com/juliomrodrigues/Arvore-de-Decisao)
- [Random Forest](https://github.com/juliomrodrigues/Random-Forest-Classificador)
- [KNN](https://github.com/juliomrodrigues/Classificador-KNN)
- [Regressão Logística](https://github.com/juliomrodrigues/Regressao-Logistica-Classificador)
- [SVM](https://github.com/juliomrodrigues/Classificador-SVM)
- [Rede Neural](https://github.com/juliomrodrigues/Classificador-Rede-Neural)
