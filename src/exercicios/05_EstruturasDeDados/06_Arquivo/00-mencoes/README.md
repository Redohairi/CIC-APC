Exercício: Menções
==================


Problema
--------

Um professor precisa de um programa para facilitar o registro que faz das menções de cada aluno todo semestre. Ele quer um programa que leia as matrículas e menções de todos os seus alunos, e os grave em um arquivo binário.

A tabela [ASCII](https://pt.wikipedia.org/wiki/ASCII) pode ser útil:


Entrada
-------

Uma linha contendo um inteiro N seguida de N linhas, cada linha contendo matrícula e menção, separados por espaço.


Saída
-----

A saída é um arquivo **binário** contendo as informações.


Exemplo(s)
----------

Supondo que cada matrícula foi gravada como um vetor de 15 caracteres e cada menção um de 3 caracteres.

| Entrada       | Saída                    |
|---------------|--------------------------|
| 2             | (arquivo binário 01.out) |
| 14/0140522 MS |                          |
| 15/0134245 MM |                          |


| Entrada       | Saída                    |
|---------------|--------------------------|
| 3             | (arquivo binário 02.out) |
| 15/0014961 MS |                          |
| 14/0140522 MS |                          |
| 16/0013232 SS |                          |
