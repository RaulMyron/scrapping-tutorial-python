# scrapping-tutorial-python
# Scrapping w/ python

Needed

```bash
pip install Scrapy
```

# Tipos de Spider

O Scrapy é uma ferramenta que pode ser usada para coletar informações de websites. Existem diferentes tipos de spiders que podem ser usados para coletar diferentes tipos de informações.

O Spider genérico é o tipo de spider mais comum e pode ser usado para coletar informações de qualquer website. Ele pega uma lista de URLs para começar e raspeia cada um deles usando um método parse.

O CrawlSpider é um tipo de spider que foi projetado para rastrear um site inteiro. Ele começa com uma URL e segue todos os links que encontrar até que tenha rastreado todo o site.

O SitemapSpider é um tipo de spider que foi projetado para extrair URLs de um mapa de site. Um mapa de site é um arquivo que lista todas as URLs de um website. O SitemapSpider pode ser usado para coletar todas as URLs de um website sem ter que seguir todos os links.

```bash
scrapy startproject helloworld
# syntax eh: scrapy genspider <name_of_spider> <website> 
scrapy genspider helloworld https://unball.github.io
```

