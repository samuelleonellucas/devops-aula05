# Arquitetura 

* As funções relacionadas ao gerenciamento das casas do jogo da velha ficarão no modulo **jogovelha.py**.

* O estado dde cada casa do jogo será representada por uma string "." para casa vazia; "X" para casa ocupada pelo 1° jogador; "O" para casa ocupada pelo 2° jogador 

* A função inicilizar() retornará uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.