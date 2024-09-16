![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![pyenv](https://img.shields.io/badge/pyenv-white?style=for-the-badge)
![poetry](https://img.shields.io/badge/poetry-d0d4fc?style=for-the-badge)
![pandas](https://img.shields.io/badge/pandas-130654?style=for-the-badge)
![matplotlib](https://img.shields.io/badge/matplotlib-222832?style=for-the-badge)
![seaborn](https://img.shields.io/badge/seaborn-white?style=for-the-badge)
![plotly](https://img.shields.io/badge/plotly-17181a?style=for-the-badge)
![ipykernel](https://img.shields.io/badge/ipykernel-3670A0?style=for-the-badge)
![pyarrow](https://img.shields.io/badge/pyarrow-222832?style=for-the-badge)

---

# Análise Exploratória de Dados (EDA)

O projeto atual tem diversos objetivos.
- Compreender e estudar tecnologias e bibliotecas python para projetos de Análise Exploratória
- Entender e extrair insights da base de dados do ENEM
- Trabalhar e gerenciar o ambiente virtual
- Compreender as primeiras etapas do CRISP-DM
- Fazer o notebook em inglês

---

# Bibliotecas

(Atualizado conforme necessário)

A biblioteca pandas, para trabalhar com os dados retirados do <a href = "https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enem">INEP</a> referente ao ENEM.

Para visualização de dados serão utilizadas as bibliotecas matplotlib, seaborn e plotly.

Para utilização de notebook (ipynb), será utilizada a biblioteca ipykernel.

Para importação dos dados em parquet, é utilizada a biblioteca pyarrow. Inicialmente os dados foram importados via CSV e salvos em parquet para melhora do desempenho.

Para gráficos interativos com o plotly, é utilizada a biblioteca nbformat.

---

# Ambiente de Desenvolvimento

- Definição da versão local da linguagem python com pyenv: 3.12.*

- Criação de ambiente virtual com venv e a ativação.

- Com Poetry, inicializado o pyproject.toml e adicionadas as dependências do projeto.

---