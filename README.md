# Programando com Python
Esse repositório é uma tradução livre [do material oficial](https://github.com/swcarpentry/python-novice-inflammation).
A tradução ainda está nos estágios iniciais e contribuições são bem-vindas.

[![GitHub release][shields_release]][swc_py_releases]
[![Create a Slack Account with us][create_slack_svg]][slack_heroku_invite]
[![Slack Status][slack_channel_status]][slack_channel_url]

Uma introdução ao Python para não-programadores usando dados de inflamação.

## Sobre a aula

Essa aula ensina programadores iniciates a escrever código modular para executar análise
de dados usando Python. A ênfase, no entanto, em ensinar príncipios de programação indenpendente
de linguagem, como automação com loops e encapsulamento com funções, vide [Melhores práticas para computação científica][best-practices] e [Práticas suficientes em computação científica][good-practices] para ler mais.

O exemplo usado nessa aula analisa um conjunto de 12 arquivos com dados simulatos de inflamação,
coletados de um estudo de um novo tratamento para artrite. É demonstrada uma forma de melhorar a análise,
automatizando-a com funções invés de repetir os passos da análise manualmente.

\*\* O preview dessa tradução, antes da publicação, está disponível em [aqui.][index]

Essa aula também está disponível em [R][R] e [MATLAB][MATLAB] (somente em inglês).

## Episódios

| # |  Episódio | Tempo | Pergunta(s) |
|--:|:---------|:----:|:------------|
| 1 | [Analisando Dados de Pacientes][episode01] | 90 | Como eu posso processar arquivos de dados tabulares em Python? |
| 2 | [Repetindo Ações com Loops][episode02] | 30 | Como eu posso fazer as mesmas operações em muitos valores diferentes? |
| 3 | [Armazenando Valores Múltiplos em Listas][episode03] | 30 | Como eu posso armazenar muitos valores juntos? |
| 4 | [Analisando Dados de Múltiplos Arquivos][episode04] | 20 | Como eu posso fazer as mesmas operações em muitos arquivos diferentes? |
| 5 | [Fazendo Escolhas][episode05] | 30 | Como meus programas podem fazer coisas diferentes baseados em valores de dados? |
| 6 | [Criando funções][episode06] | 30 | Como eu posso definir novas funções?<br>Qual é a diferença entre definir e chamar uma função?<br>O que acontece depois que eu chamo uma função? |
| 7 | [Erros e Exceções][episode07] | 30 | Como o Python reporta erros?<br>Como eu posso lidar com erros em programas Python? |
| 8 | [Programação Defensiva][episode08] | 30 | Como eu posso tornar meus programas mais confiáveis? |
| 9 | [Debugging][episode09] | 30 | Como eu posso debuggar meu programa? |
|10 | [Programas de linha de comando][episode10] | 30 | Como eu posso contribuir para escrever programas Python que funcionem como linhas de comando Unix? |


## Contribuindo
[![Travis Build Status][travis_svg]][travis_url]

Nós apreciamos todas as contribuições para melhorar a aula!
Responsáveis farão seu melhor para ajudar se você tiver qualquer pergunta,
preocupação, ou sentir alguma dificuldade com isso.

Gostaríamos que você se familiarizasse com nosso [Guia de Contribuição](CONTRIBUTING.md)
e deem uma olhada nas [orientações mais detalhadas][lesson-example] para formatação adequada,
formas de renderizar a aula localmente, e até como escrever novos episódios!

**Nota do tradutor**: Essa é uma tradução livre do material original, porém as regras de contribuição
são as mesmas.

## Responsáveis

Responsáveis pela aula são [Trevor Bekolay][trevor_bekolay], [Maxim Belkin][maxim_belkin],
[Anne Fouilloux][anne_fouilloux], [Valentina Staneva][valentina_staneva],
[Mike Trizna][mike_trizna], e o [criador][swc_history] of Software Carpentry:
[Greg Wilson][greg_wilson]

Responsável pela tradução para português é [Vini Salazar][vini_salazar].

## Autores
Uma lista de contribuidores para a aula pode ser encontrada em [AUTHORS](AUTHORS)

## Licença
Instructional material from this lesson is made available under the Creative
Commons Attribution (CC BY 4.0) license. Except where otherwise noted, example
programs and software included as part of this lesson are made available under
the MIT license. For more information, see [LICENSE.md](LICENSE.md).

## Citation
To cite this lesson, please consult with [CITATION](CITATION)

[lesson-example]: https://carpentries.github.io/lesson-example
[anne_fouilloux]: https://github.com/annefou
[maxim_belkin]: https://github.com/maxim-belkin
[mike_trizna]: https://github.com/MikeTrizna
[trevor_bekolay]: http://software-carpentry.org/team/#bekolay_trevor
[valentina_staneva]: http://software-carpentry.org/team/#staneva_valentina
[greg_wilson]: https://github.com/gvwilson
[vini_salazar]: https://github.com/vinisalazar
[swc_history]: https://software-carpentry.org/scf/history/
[best-practices]: http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745
[good-practices]: http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510
[R]: https://github.com/swcarpentry/r-novice-inflammation
[MATLAB]: https://github.com/swcarpentry/matlab-novice-inflammation
[shields_release]: https://img.shields.io/github/release/swcarpentry/python-novice-inflammation.svg
[swc_py_releases]: https://github.com/swcarpentry/python-novice-inflammation/releases
[create_slack_svg]: https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg
[slack_heroku_invite]: https://swc-slack-invite.herokuapp.com
[slack_channel_status]: https://img.shields.io/badge/Slack_Channel-swc--py--inflammation-E01563.svg
[slack_channel_url]: https://swcarpentry.slack.com/messages/C9Y0L6MF0
[travis_svg]: https://travis-ci.org/swcarpentry/python-novice-inflammation.svg?branch=gh-pages
[travis_url]: https://travis-ci.org/swcarpentry/python-novice-inflammation
[index]: http://vinisalazar.github.io/python-iniciante-inflamacao/
[episode01]: http://vinisalazar.github.io/python-iniciante-inflamacao/01-numpy/index.html
[episode02]: http://vinisalazar.github.io/python-iniciante-inflamacao/02-loop/index.html
[episode03]: http://vinisalazar.github.io/python-iniciante-inflamacao/03-lists/index.html
[episode04]: http://vinisalazar.github.io/python-iniciante-inflamacao/04-files/index.html
[episode05]: http://vinisalazar.github.io/python-iniciante-inflamacao/05-cond/index.html
[episode06]: http://vinisalazar.github.io/python-iniciante-inflamacao/06-func/index.html
[episode07]: http://vinisalazar.github.io/python-iniciante-inflamacao/07-errors/index.html
[episode08]: http://vinisalazar.github.io/python-iniciante-inflamacao/08-defensive/index.html
[episode09]: http://vinisalazar.github.io/python-iniciante-inflamacao/09-debugging/index.html
[episode10]: http://vinisalazar.github.io/python-iniciante-inflamacao/10-cmdline/index.html
