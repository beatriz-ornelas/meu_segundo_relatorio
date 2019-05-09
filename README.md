Meu segundo relatório R
================
Beatriz Ornelas

Vamos mostrar aqui alguns códigos e funções do R.

Primero é necessário instalar os pacotes que iremos utilizar e depois carregá-los.

Para carregar o pacote basta usar o comando library. Vamos carregar os pacotes tidyverse e gapminder.

``` r
library("tidyverse")
library("gapminder")
```

O pacote gapminder traz um dataset. Vamos ver.

Primeiro vamos identificar as 6 primeiras linhas do dataset gapminder.

``` r
head(gapminder)
```

    ## # A tibble: 6 x 6
    ##   country     continent  year lifeExp      pop gdpPercap
    ##   <fct>       <fct>     <int>   <dbl>    <int>     <dbl>
    ## 1 Afghanistan Asia       1952    28.8  8425333      779.
    ## 2 Afghanistan Asia       1957    30.3  9240934      821.
    ## 3 Afghanistan Asia       1962    32.0 10267083      853.
    ## 4 Afghanistan Asia       1967    34.0 11537966      836.
    ## 5 Afghanistan Asia       1972    36.1 13079460      740.
    ## 6 Afghanistan Asia       1977    38.4 14880372      786.

Hum. Temos já algumas informações relevantes.

Agora vamos ver quantas linhas no total tem o dataset gapminder.

``` r
nrow(gapminder)
```

    ## [1] 1704

A partir daqui podemos trabalhar com outras funções e informações.
