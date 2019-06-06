---
layout: lesson
root: .
permalink: index.html
---

A melhor forma de aprender a programar é fazer algo útil,
então essa introdução ao Python será construída para realizar uma tarefa científica comum:
**análise de dados**.

### Artrite inflamatória
Estamos estudando **inflamação em pacientes** que receberam um novo tratamento para artrite, e
precisam analisar os seus doze primeiros conjuntos de dados de inflamação diária. Os conjuntos de dados são armazenados em
[arquivos separados por vírgula]{{ page.root }}/reference/#comma-separated-values), no format CSV:

- cada linha contém informação de um único paciente.
- cada coluna representa um dia, sucessivamente.

As três primeiras linhas do nosso arquivo parecem com isso:
<!-- The first three rows of our first file look like this: -->
~~~
0,0,1,3,1,2,4,7,8,3,3,3,10,5,7,4,7,7,12,18,6,13,11,11,7,7,4,6,8,8,4,4,5,7,3,4,2,3,0,0
0,1,2,1,2,1,3,2,2,6,10,11,5,9,4,4,7,16,8,6,18,4,12,5,12,7,11,5,11,3,3,5,4,4,5,5,1,1,0,1
0,1,1,3,3,2,6,2,5,9,5,7,4,5,4,15,5,11,9,10,19,14,12,17,7,12,11,7,4,2,10,5,4,2,2,3,2,2,1,1
~~~
{: .source}
Onde cada número representa o número de sensações inflamatórias que um paciente sofreu em um dado dia.
Por exemplos, o valor "6" na linha 3, coluna 7 do conjunto de dados acima significa que o terceiro
paciente estava sofrendo de inflamação seis vezes no sétimo dia do estudo clínico.
<!-- Each number represents the number of inflammation bouts that a particular patient experienced on a
given day. For example, value "6" at row 3 column 7 of the data set above means that the third
patient was experiencing inflammation six times on the seventh day of the clinical study. -->

Então, queremos:
<!-- So, we want to: -->

1. Calcular a média de inflamação por dia entre todos os pacientes.
2. Plotar o resultado e discutir os dados com o colega.
<!-- 1. Calculate the average inflammation per day across all patients.
2. Plot the result to discuss and share with colleagues. -->

Para fazer tudo isso, teremos que aprender um pouco de programação.
<!-- To do all that, we'll have to learn a little bit about programming. -->

> ## Pré requisitos
> Você precisa entender os conceitos de **arquivos** e **diretórios** e como iniciar um interpretador
> Python antes de começar essa aula. Essa aula menciona o Jupyter Notebook, mas você
> pode usar qualquer interpretador Python mencionado no [Setup](setup/).
>
> Os comandos dessa aula são em **Python 3**.
{> .prereq}

<!-- > ## Prerequisites
>
> You need to understand the concepts of **files** and **directories** and how to start a Python
> interpreter before tackling this lesson. This lesson sometimes references Jupyter
> Notebook although you can use any Python interpreter mentioned in the [Setup](setup/).
>
> The commands in this lesson pertain to **Python 3**.
{: .prereq} -->

### Começando
Para começar, siga as instruções na página de "[Setup](setup/)" para fazer download dos
dados e instalar um interpretador Python.
<!-- ### Getting Started
To get started, follow the directions on the "[Setup](setup/)" page to download data
and install a Python interpreter. -->
