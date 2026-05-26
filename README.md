# Projeto de Mineração de Dados: Análise de padrões de consumo de filmes com K-Means e regras de associação

## Sobre o projeto
O foco deste trabalho é a mineração de dados de arquivos cinematográficos baseados na base MovieLens, realizando a extração de conhecimento e a descoberta automatizada de regras de associação a partir dos títulos e gêneros dos filmes.

## Tecnologias e conceitos
* Linguagem: Python.
* Bibliotecas Principais:
    - pandas e numpy (manipulação matricial e engenharia de dados vetorizada).
    - scikit-learn (algoritmo K-Means e métricas de validação de clusters).
    - mlxtend (algoritmo Apriori e extração de regras de associação).
    - matplotlib / seaborn (visualização gráfica dos clusters e curvas de otimização).

## Preparação da base

1. Faça o clone do projeto:
   git clone https://github.com/danieltefi/Projeto_Mineracao_Dados.git

2. Preparação da base de dados (obrigatório):
   * Baixe os arquivos da base de dados oficial diretamente através do link: https://files.grouplens.org/datasets/movielens/ml-latest.zip
   * Descompacte o arquivo .zip baixado em seu computador.
   * Crie uma pasta chamada `dados` dentro do diretório do projeto clonado.
   * Mova apenas os arquivos `movies.csv` e `ratings.csv` para dentro dessa nova pasta.
   * Certifique-se de que o caminho final estruturado no seu computador seja exatamente:
     Projeto_Mineracao_Dados\dados\movies.csv
     Projeto_Mineracao_Dados\dados\ratings.csv

## Estrutura de Arquivos
```text
├── dados/                              # Pasta criada manualmente para armazenar a base
│   ├── movies.csv                      # Metadados dos filmes (gêneros e títulos)
│   └── ratings.csv                     # Base massiva de avaliações de usuários
├── .gitignore                          # Define arquivos que o Git deve ignorar
├── analisefilme.ipynb                  # Jupyter Notebook com mineração de dados
└── Relatorio_Projeto_Mineracao_Dados   # Relatório do projeto
```