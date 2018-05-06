# Cinema
Construindo um algoritmo para verificar os filmes em cartaz (do dia) no Cinemark da cidade de Natal.
As informações obtidas são:
 - Data de lançamento do filme
 - Título do filme
 - Horário de seção disponível
 - Idioma
 - Ranking (Nota do usuário)

Site para consulta: Adoro Cinema.

# Pré requisitos

Para executar o projeto é necessário ter instalado os seguintes pacotes:
- Python 3
  * Requests
  * BeautifulSoup
  * Pandas
- Jupyter Notebook

# Para executar o projeto

```
  jupyter notebook
```

# Imports do projeto

<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/cinema/images/imports.png"></p>

# Funções de requisições

Funções para fazer o download das páginas e verificar se a URL retorna um HTML.
<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/cinema/images/functions.png"></p>

# Analisando os dados obtidos

Fazendo o tratamento dos dados obtidos, selecionando os elementos desejados (Pegando os elementos pelos names das class)
e ordenando os filmes de acordo com a classificação dos usuários (do maior para o menor)

<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/cinema/images/processing.png"></p>

# Resultado

Exibindo em um DataFrame o resultado
<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/cinema/images/result.png"></p>

# Autor
- Jilcimar Fernandes
