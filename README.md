# appgen - tool for generate applications

## Description:
### This tool helps create the structure of an application, including database
### For now it generates for Python and PHP


## Instalation

- Download appgen: [appgen files](https://github.com/ortizdavid/appgen-files)
- Add appgen to **PATH** environment variable


## Usage:

**appgen** **-name** application_name **-lang** language **-type** application_type **-db** <database>

##  Commands:
- **appgen**:     First command
- **list-langs**: List all supported languages and applications
- **help**:       Shows helps for appgen
- **-name**:      Project Name
- **-lang**:      Programming Language
- **-type**:      Type of application (mvc, api)
- **-db**:        database 

## Examples:

1. Create a MVC App with Python and MySQL:
    ``
    appgen -name PythonMVC -lang python -type mvc -db mysql 
    ``

2. Creates an API with Python and Postgres:
    ``
    appgen -name PythonAPI -lang python -type api -db postgres    
    `` 

3. Show help comands:
    ``
    appgen help 
    ``   

4. List all suportded languages:
    ``
    appgen list-langs 
    ``                                                      

## Author:
- Name:         Ortiz de Arcanjo António David
- Phone:        +244 936 166 699
- Email:        ortizaad1994@gmail.com
- Github:       https://www.github.com/ortizdavid
- LinkedIn:     https://www.linkedin.com/in/ortiz-david


## AppGen Flow

<img src="AppGen Flow.jpg">


## Generating API

![Generating API](Appgen-API.gif)




comentário no facebook:

Ferramenta AppGen
Appgen (Application Generator) é uma aplicação de linha de comandos que serve para criar aplicações, estruturar o projecto, gerar a base de dados e instruções para executar. 
Alguns frameworks e linguagens têm como filosofia não impor muitos padrões no desenvolvimento de aplicações e deixar a organização do projecto nas mãos do programador, de modo a tomar as suas próprias decisões. Ex: Go, PHP, Python(com Flask).
Para muitos programadores, é difícil organizar um projecto. Torna-se complicado saber como onde encaixar cada parte do código. Logo, o appgen ajuda nesse problema.
Funcionalidades Principais
- Gerar as pastas do projectos;
- Gerar arquivos estáticos (css, js):
- Gerar arquivos de biblioteca (Bootstrap, JQuery)
- Gerar Models e Controllers;
- Gerar o Script da Base de Dados (Postgres e MySQL);
- Arquivos para o GitHub(README e .gitignore);
- Coleções para teste no Postman (Postman Collections);
- Gerar arquivos de configuração.
Alguns Comandos do appgen
 - Criação: appgen –name <aplicação> -lang <linguagem> -type <tipo> -db <sgbd >
- Ajuda: appgen help 
- Tipos de projecto: appgen list-langs
Vantagens
- Exemplo com cadastro, login, logout, upload de arquivos
- Facilidade no uso(comandos claros);
- Rapidez na geração de código;
- Tamanho (menos de 3MB);
- Comandos de ajuda muito;
- Geração de código simples, arquitectura simples.
Observação
Inicialmente a AppGen apenas suporta a linguagem Python, gerando projectos API e MVC, com o framework Flask. Futuramente, haverá suporte para PHP e Golang.
Exemplos
Usando a ferramenta appgen vamos gerar 2 aplicações:
- Gerar uma API REST com Python e Postgres;
- Gerar uma aplicação MVC com Python e MySQL.
Link para Download
https://github.com/ortizdavid/appgen-files

