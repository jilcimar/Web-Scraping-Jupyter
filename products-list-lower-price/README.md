# Introdução ao Web Scraping - Lista de produtos pelo menor preço

Código de introdução a Web Scraping listando todos os notebooks da loja Submarino
e ordenando pelo menor preço.

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

# Imports do Projeto

<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/products-list-lower-price/images/imports.png"></p>

# Funções de requisições

Funções para fazer o download das páginas e verificar se a URL retorna um HTML.
<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/products-list-lower-price/images/functions.png"></p>

# Analisando os dados obtidos

Fazendo o tratamento dos dados obtidos, selecionando os elementos desejados (Pegando o elemento pelo name da class)
e ordenando os produtos por preço (do menor para o maior)

<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/products-list-lower-price/images/treatment.png"></p>

# Resultado

Exibindo em um DataFrame o resultado
<p align="center"><img src="https://github.com/jilcimar/web-scraping-jupyter/blob/master/products-list-lower-price/images/result.png"></p>

# Autor
- Jilcimar Fernandes
