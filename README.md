# Projeto Meteorologia

Aplicação web de meteorologia desenvolvida como projeto pessoal para praticar os fundamentos de **HTML, CSS e JavaScript**.

A aplicação permite pesquisar uma cidade do mundo e consultar informações atuais sobre as condições meteorológicas por meio do consumo da **OpenWeather API**.

## Funcionalidades

* Pesquisa de cidades do mundo todo.
* Consumo de dados meteorológicos por meio da OpenWeather API.
* Exibição da temperatura atual.
* Exibição da temperatura máxima.
* Exibição da temperatura mínima.
* Exibição da umidade.
* Exibição da velocidade do vento.
* Tratamento de cidades não encontradas.
* Exibição de uma imagem de erro (`404.svg`) quando a cidade pesquisada não é encontrada.

## Tecnologias utilizadas

* HTML
* CSS
* JavaScript
* OpenWeather API
* Font Awesome

## Objetivo do projeto

Este projeto foi desenvolvido como parte dos meus estudos em desenvolvimento web, com o objetivo de praticar conceitos básicos, incluindo:

* Estruturação de páginas com HTML.
* Estilização com CSS.
* Lógica de programação com JavaScript.
* Consumo e utilização de dados provenientes de uma API.
* Tratamento de situações em que a cidade pesquisada não é encontrada.

## Integração com API

O projeto utiliza a **OpenWeather API** para obter os dados meteorológicos das cidades pesquisadas.

A requisição utiliza parâmetros como:

* Cidade pesquisada.
* Unidade de temperatura em Celsius.
* Idioma dos dados em português.

## Uso da API

Por questões de segurança, nenhuma API Key pessoal é disponibilizada neste repositório.

Para executar o projeto localmente:

1. Crie uma conta na [OpenWeather](https://openweathermap.org/).
2. Gere uma API Key.
3. Abra o arquivo `script.js`.
4. Substitua `SUA_API_KEY_AQUI` pela sua própria chave.
5. Execute o projeto localmente.

Cada usuário deve utilizar sua própria API Key para realizar as consultas à API.

## Tratamento de erro

Quando a cidade pesquisada não é encontrada, a aplicação apresenta uma mensagem informando o usuário e exibe uma imagem de erro (`404.svg`).

## Segurança

A API Key utilizada durante o desenvolvimento local não é publicada neste repositório.

O código disponibilizado no GitHub contém apenas um campo reservado para que o usuário informe sua própria API Key.

## Status

Projeto concluído como projeto pessoal de estudo.

## Autor

Raul Reis

GitHub: [raulreis-rj](https://github.com/raulreis-rj)


