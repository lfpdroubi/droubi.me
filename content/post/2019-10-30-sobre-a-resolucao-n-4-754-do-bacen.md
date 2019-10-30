---
title: Sobre a Resolução nº 4.754 do Bacen
author: Droubi
date: '2019-10-30'
slug: sobre-a-resolução-n-4-754-do-bacen
categories:
  - congressos
  - avaliação de imóveis
  - Machine Learning
tags:
  - cobreap
  - Bacen
image:
  caption: ''
  focal_point: ''
---


Ficou um sentimento de indignação em relação à [resolução n.º 4.754 do Bacen](https://www.bcb.gov.br/estabilidadefinanceira/exibenormativo?tipo=Resolu%C3%A7%C3%A3o&numero=4754) permitindo a “avaliação automática” de imóveis pelos próprios bancos, que se dará provavelmente através de *Machine Learning* (ML), dispensando o trabalho dos peritos avaliadores.

Além dos problemas óbvios que advirão da piora da regulação do setor bancário, que aliás é o que está na raiz da crise do *subprime* que estourou em 2008, a resolução conta com problemas teóricos básicos.

Em especial, na sua [exposição de motivos](https://www.bcb.gov.br/pre/normativos/busca/downloadVoto.asp?arquivo=/Votos/CMN/201968/Voto_0682019_CMN.pdf), o Bacen alega, entre outras coisas, que *"diferentemente do cenário em que a Resolução nº 4.271, de 2013, foi editada, atualmente o mercado imobiliário brasileiro dispõe de vastas fontes de informações e de soluções que permitem a adoção de modelos estatísticos de precificação tão confiáveis quanto as avaliações efetuadas por peritos avaliadores."*

Este ao meu ver é a maior falha dessa resolução, que desconsiderou toda a comunidade da Engenharia, sem ao menos consultá-la, em troca de *"modelos estatísticos de precificação".*

Inicialmente, deve haver uma reflexão a respeito do que é a Engenharia e o seu papel na sociedade e, por conseguinte, o que é a Engenharia de Avaliações e a sua importância.

Para isto, inicialmente vou fazer um paralelo entre a Engenharia Estrutural (outra área que sofre muito na atualidade com os projetos elaborados automaticamente por *software* de cálculo) e a Física, ciência onde se concentram talvez as pessoas mais inteligentes que a humanidade já produziu.

Bem, todos sabemos que qualquer físico é capaz de responder quais são as leis da Física que fazem um edifício ou outras estruturas da Engenharia ficarem em pé ao invés de desabarem: tanto para um edifício, quanto para uma ponte, viaduto ou passarela, os princípios físicos envolvidos são essencialmente os do equilíbrio: somatória de forças na vertical e horizontal e somatória de momentos em relação aos eixos de um sistema ortogonal de referência, todas iguais a zero.

Nem por isso está um Físico habilitado a projetar ou construir um edifício ou uma obra-de-arte. Mesmo com os magníficos *software* existentes, que hoje custam milhares de reais, ainda é indispensável a ART de um Engenheiro, que tem obrigação de verificar o que faz o *software*, que aliás não garante nada (ninguém pode processar o autor de um *software* pela queda de um edifício).

E os motivos são que as atividades envolvidas são muito mais complexas do que a simples verificação do equilíbrio estático e dinâmico: é preciso uma boa dose de bom-senso, é preciso saber como se dão as atividades dentro de um canteiro de obras, as diversas fases de construção, do processo de fabricação e recebimento do material em obra, das atividades relacionadas à fiscalização de todo o processo, a qualidade possível e almejada da execução, entre muitas outras coisas. E acima de tudo, é preciso saber qual a margem de segurança necessária para fazer tudo isso, e, no caso da Engenharia Civil, sem a construção de um protótipo ou algo que o valha. Em poucas palavras, é preciso quantificar o risco de algo dar errado, sem esquecer dos custos, fazendo assim uma obra ao mesmo tempo econômica, eficaz e segura.

Da mesma maneira, a atividade de Avaliação de Imóveis não pode ser simplesmente substituída por um algoritmo programado sabe-se lá por quem e de que forma.

Assim como a Engenharia Estrutural se utiliza dos princípios físicos do equilíbrio para projetar uma Estrutura, a Engenharia de Avaliações se baseia em métodos estatísticos para a sua atividade. E da mesma forma não há estatístico que vá substituir todo o saber de um Engenheiro Civil na Avaliação de um imóvel, simplesmente por conhecer, talvez até melhor do que nós, Engenheiros, os princípios da estatística seja ela frequentista ou bayesiana. Muito menos um algoritmo qualquer desenvolvido por um estatístico, economista, a Fundação Instituto de Pesquisas Econômicas da FGV ou quem quer que seja.

Ainda sim, há de se esclarecer que mesmo a comunidade de ML se distingue da comunidade dos estatísticos. Apesar de que o que conhecemos como ML não ser constituída de nada mais do que Estatística, ainda que com uma nova roupagem (na comunidade de ML os regressores são chamados de *features*, por exemplo) aplicadas a grandes massas de dados, ou *Big data* (ver Matloff, 2017, p. xxxiii).

Além do mais, os maiores estatísticos hoje são receosos quanto aos procedimentos aplicados cegamente na comunidade de ML: eles sabem que não há panaceia, ou seja, não existe um único método estatístico que seja capaz de resolver a todos os problemas (ver Matloff, 2017, 348).

Mesmo a validação cruzada, vendida pela comunidade de ML como a última novidade em termos de consistência, não pode ser considerada nenhuma garantia. Aliás, nem consistente, estatisticamente falando, ela é (Matloff, 2017, 348).

A grande verdade é que qualquer que seja a abordagem que os bancos venham a utilizar para o algoritmo de "avaliação automática", esta abordagem será falha. Como profetiza Matloff:

Data science should not be a "spectator sport"; the methodology is effective only if the users *participate*. Avoid ceding the decision making to the computer output. For example: a) Statistical significance does not imply practical importance, and conversely. b) A model is just that -– just an approximation to reality, hopefully useful but never exact. c) Don’t rely solely on variable selection algorithms to choose your model. d) "Read directions before use" -– make sure you understand what a method really does before employing it (Matloff, 2017, 47-48).

Além disso, diversos avanços tem sido feitos tanto nas Ciências Estatísticas e a Engenharia de Avaliações está e deverá se manter sempre atenta a isto, adaptando aos poucos o que há de mais novo nas Ciências Estatísticas, porém de maneira que satisfaça às necessidades da Engenharia de Avaliações, afinal, como já ponderei, a Engenharia de Avaliações utiliza-se da Estatística, mas a Estatística **não é** a Engenharia de Avaliações.

E o maior exemplo deste último aspecto, a meu ver, se deu na palestra do Prof. Norberto Hochheim sobre regressão polinomial no [XX COBREAP](http://www.cobreap.com.br/2019/): o método de regressão polinomial em si não pode ser visto como uma novidade, mas os recentes achados de Matloff et. al. (2018), mostrando que Redes Neurais, um algoritmo muito utilizado pela comunidade de ML nada mais é do que uma forma de regressão polinomial, vem muito a calhar para a Engenharia de Avaliações. Claro, pois além do método de regressão polinomial ter se mostrado mais eficiente do que as próprias redes neurais, a regressão polinomial é muito mais fácil de ser explicada do que uma rede neural, que são consideradas pelos próprios estatísticos como verdadeiras caixas pretas (Matloff et. al. 2018).

Obviamente que muito trabalho ainda deverá ser feito para a correta aplicação das regressão polinomial na Engenharia de Avaliações. Eventualmente serão necessários ajustes normativos, baseados em futuros estudos que eventualmente mostrarão os potenciais da aplicação do método na área e também os seus problemas.

Houve reações negativas da Comunidade durante a apresentação, especialmente quanto à aplicação de análise de componentes principais (ACP), por exemplo, questionando-se a dificuldade de se explicar isto.

Saliente-se que a ACP não é indispensável na regressão polinomial. Além disto, haja vista que a tendência é que trabalhemos cada vez mais com um número maior de dados, ela pode até se tornar dispensável, visto que ela se destina a evitar a multicolinearidade, o que não ocorre a menos que o número de dados do modelo seja pequeno em relação ao número de parâmetros.

Claro que o ideal é que houvesse fatores do Ibape-SP disponíveis em quaisquer localidades.

Porém, a realidade é mais complexa. Às vezes torna-se necessário algum grau de complicação.

No entanto, deve-se convir que muito pior do que explicar ACP a um cliente é tentar explicar o funcionamento de uma rede neural, que até pouco tempo nem os estatísticos eram capaz de fazê-lo.

## Contexto de predição e descrição na Estatística e na Engenharia de Avaliações

Na Estatística a utilização de modelos de regressão linear, por exemplo, se divide em aplicações voltadas a predição de valores e a aplicaçãoes voltadas à descrição.

Na Engenharia de Avaliações muitas vezes as duas coisas se confundem.

Por exemplo: pode-se estar interessado em saber o valor de um novo imóvel dentro de um mercado onde se efetuou uma amostragem através de um modelo de regressão linear, mas normalmente também se está interessado em saber como se chegou a este valor, ou seja, quais foram as variáveis utilizadas para isto e como estas variáveis entraram na composição do valor.

O simples fato de uma variável qualquer ter um efeito ao contrário do que se prevê, pode levar ao abandono de um modelo por um outro modelo onde isto se verifica, ainda que o segundo modelo tenha um menor poder de predição.

Em conversas informais no COBREAP com alguns colegas, percebi que muitos entendem que esta abordagem deveria ser, no mínimo, relaxada.

Eu não posso deixar de concordar com eles, haja vista que o ideal para a Avaliação de um imóvel é que se tenha o máximo possível de poder de predição. O paradoxo de Simpson, aliás, prevê que a adição de um regressor ao modelo pode modificar completamente o efeito de outro regressor.

Porém, imaginem o que pode ocorrer numa perícia se o assistente técnico de uma das partes descobrir que, no modelo do Sr. Perito, um acréscimo marginal de área construída diminui o valor total da avaliação do imóvel em discussão ou vice-versa.

Enfim, é por estas e por outras que chamamos de Engenharia de Avaliações e não de Estatística de Avaliações: não basta simplesmente fazer um modelo estatístico, por melhor que seja, e prever com este modelo o valor de um novo imóvel. Por melhor que seja esta previsão, modelos estatísticos são puramente matemáticos, não são possuidores de **bom-senso**, principal qualidade de um bom **ENGENHEIRO**.

## Referências

MATLOFF, N. **Statistical regression and classification: From linear models to machine learning**. Boca Raton, Florida: Chapman & Hall, 2017

MATLOFF, Norman; CHENG, Xi; KHOMTCHOUK, Bohdan; MOHANTY, Pete. **Polynomial regression as an alternative to neural nets**. 2018. Disponível em: < https://arxiv.org/abs/1806.06850>. Acesso em out. 2018.
