# Iniciando introdução a interface HTML com o python
Primeiro baixamos o UV Astral que substitui o pip.

## Verificando e atualizando o Python
verificamos a versão do python que estavamos usando com o comando "python -V" e atualizamos com o "uv install python 3.15.0"

## projeto_com_Flask
criamos a pasta projeto_com_Flask onde iniciamos ajustando a versão do python e criando o primeiro arquivo app.py

## Importação com o Flask
importamos: 
- o flask, que é responsável por rotas URL
- o render_template, responsável por gerar a página HTML
- o request que atende a requisições, busca dados e fornece parâmetros
- e o escape para passar variáveis de texto para o HTML que será usado

## Criação de rotas
Usamos o @app.route("/caminho") seguido de uma função que retornava uma string com o nome digitado na URL ou "Flask!"

## Criação do HTML
No HTML criamos a estrutura e adicionamos uma estrutura de decisão para verificar se foi informado algum nome para ser colocado na string mostrada, caso contrário, será mostrado Flask.

## Controle de execução do código 
Para esse controle usamos uma condição (__name__ == "__main__") que faz com que o programa não rode inteiro por conta própria e sim apenas o Flask.