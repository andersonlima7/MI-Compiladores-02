﻿# MI-Compiladores-02

Anexo A: Características gerais da linguagem

1) Todo o código-fonte deve ser feito em único arquivo.
2) A linguagem permite a declaração de variáveis globais e locais, mas exige a declaração de constantes
apenas como globais.
3) Deve ser possível declarar múltiplas variáveis, constantes ou objetos do mesmo tipo na mesma linha.

4) As declarações de uma ou mais constantes devem ser feitas dentro de um bloco que se inicia com a palavra
const.
5) As declarações de uma ou mais variáveis devem ser feitas dentro de um bloco que se inicia com a palavra
variables.
6) As declarações de um ou mais objetos devem ser feitos dentro de um bloco que se inicia com a palavra
objects. Um objeto é uma instância de uma classe.
7) A inicialização de um objeto pode ser feita através de um construtor. Um construtor se inicia com a palavra
constructor, seguida da lista de parâmetros reais separados por vírgula entre parênteses.
8) Os objetos possuem atributos e a declaração de atributos é feita da forma descrita no item 5.
9) Os objetos possuem métodos. As declarações de um ou mais métodos devem ser feitos dentro de um bloco
que se inicia com a palavra methods.
10) Cada método deve conter inicialmente o tipo de retorno, seguido do nome do método, seguido da lista de
parâmetros formais separados por vírgula entre parênteses. O valor de retorno se dará através da palavra
return. Um método pode não retornar nenhum valor, neste caso, o tipo de retorno é void.
11) A classe main é responsável por iniciar o programa e cada programa deve conter uma única classe main.
12) As chamadas aos métodos serão realizadas da seguinte forma: nome do objeto, seguido por ->, seguido
pelo nome do método, seguido pela lista de parâmetros reais separados por vírgula entre parênteses.
13) O acesso aos atributos dos objetos será da seguinte forma: nome do objeto, seguido por . (ponto), seguido
pelo nome do atributo.
14) A palavra reservada this deverá ser usada dentro dos métodos, para diferenciar variáveis e atributos.
15) Será permitido o uso de identificadores de mesmo nome, desde que em escopos diferentes.
16) A linguagem permite o uso de vetores e matrizes. Deve ser possível acessar (ler ou inserir) os elementos
de um vetor ou matriz.
17) Uma classe pode herdar de outra classe usando a palavra extends.
18) Delimitadores { e } marcam início e fim de blocos, respectivamente (de comandos, declaração de variáveis,
constantes, objetos, etc.).
19) A linguagem permite o uso de expressões relacionais, lógicas e aritméticas.
20) Uma expressão aritmética resulta em um único valor aritmético (int ou real). Uma expressão relacional ou
lógica resulta em um único valor booleano (true ou false).
21) Comandos:
▪ if .. then .. else: Na condição do comando só são permitidas as expressões relacionais, lógicas ou valores
booleanos. O comando else não é obrigatório.
▪ for: Na condição do comando só são permitidas as expressões relacionais, lógicas ou valores booleanos.
▪ print: O comando iniciará com a palavra print e o que deverá ser impresso entre parênteses, finalizando
com ponto-e-vírgula. O comando pode imprimir cadeias de caracteres, valores de constantes, variáveis e
atributos de objetos.
▪ read: O comando iniciará com a palavra read e o que deverá ser lido entre parênteses, finalizando com
ponto-e-vírgula. O comando pode ler variáveis e atributos de objetos.
