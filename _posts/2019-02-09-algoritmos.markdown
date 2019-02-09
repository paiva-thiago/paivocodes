---
layout: post
title:  "Algoritmos"
date:   2019-02-10 18:00:25 -0300
categories: introdução
tags: none
image: /assets/article_images/2019-02-04-ola-mundo/desktop.JPG
---

Para a execução de qualquer aplicação, é necessário que entendamos o processo de construir algoritmos.

> Algo o que?

Algoritmos são sequências de instruções que enviamos a uma máquina. Temos paralelos no nosso cotidiano.

Em um tempo em que Waze ou Google Maps eram possíveis de existir apenas em obras de ficção científica, a forma que encontrávamos para chegar a algum lugar, era pedindo informações. Principalmente para taxistas. Por muito tempo taxistas e donos de banca eram meus wazes. E geralmente as instruções para chegar a um determinado local sempre eram coisas do tipo:

> "Meu filho, para chegar lá é fácil, siga em frente, vire a segunda à direita, a terceira a esquerda, e você chegará lá!"

Temos algumas instruções

1. Seguir em frente por duas quadras;
2. Virar à direita;
3. Seguir por 3 quadras;
4. Virar a esquerda
5. Fim.

Estas instruções podem ser classificadas como algoritmos. Vamos criar uma linguagem fictícia com dois comandos, andar e virar:

<pre>
    andar(2)
    virar(direita)
    andar(3)
    virar(esquerda)
</pre>

Estamos chegando algo próximo de uma máquina. Mas tem algo bem importante. Em alguns momentos, quando passamos instruções a uma outra pessoa, omitimos informações por elas estarem implícitas ao nosso interlocutor. Vamos lembrar sempre que para uma máquina não existe algo implícito, então é importante explicar bem explicado, como esta tirinha do [Vida de Programador](https://vidadeprogramador.com.br/2011/03/22/logica-de-programacao/):

![Programadores](/assets/article_images/2019-02-09-algoritmos/tirinha25.png)

Na tirinha acima, o que ela quis passar:

<pre>
    ir ao mercado
    trazer 6 ovos
    se tiver batatas
        trazer 9 batatas
</pre>

E o que ele entendeu:
<pre>
    ir(mercado)
    trazer(ovos,6)
    se(tiver(batatas))
        trazer(ovos,9)
</pre>

Digamos que ele não atualizou as variáveis.

E o que são variáveis? Deixemos para o próximo episódio!

