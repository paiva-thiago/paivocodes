---
layout: post
title:  "Ser ou não ser"
date:   2019-02-27 08:00:00 -0300
categories: introdução
tags: none
image: /assets/article_images/2019-02-27-ser-ou-nao-ser/tobeornottobe.jpg
---

Ser ou não ser? Existe ou não existe? ~~Morreu ou foi pra Record?~~  Verdadeiro ou falso?

Em programação é essencial realizar comparações. Validações de dados, comparações de informações e afins. Para isto temos os valores de tipo **booleanos**. Ele pode ser de dois tipos: **Verdadeiro** ou **Falso**.

Para obtermos estas informações temos *operadores lógicos*. 

1. Maior (**>**);
2. Maior ou igual (**>=**);
3. Menor (**<**);
4. Menor ou igual (**<=**);
5. Igual (**=**, e em boa parte das linguagens de programação **==**);
6. Diferente (**!=**)

vamos fazer um teste, no console do nosso browser ou no [REPL](http://repl.it/languages/javascript):

```javascript
    let a = 2;
    let b = 3;
    console.log('a é maior que b? '+(a>b));
    console.log('a é maior ou igual a b? '+(a>=b));
    console.log('a é menor que b? '+ (a<b));
    console.log('a é menor ou igual a b? '+(a<=b));
    console.log('a é igual a b? '+(a==b));
    console.log('a é diferente a b? '+(a!=b));
```

Use outros valores para a e b e vai executando!

O `let`, assim como o `var`, é utilizado para declarar variáveis no javascript. Nos próximos posts veremos quais contextos eles se aplicam.

Também temos operadores para trabalhar com estes valores booleanos:

1. E **&&**;
2. OU **||**;
3. NEGAÇÃO - ele inverte o valor booleano (**!** - notou que o sinal de diferente lá em cima é um *não igual*?)

Abaixo uma "tabela verdade" simples acompanhando o **e** e o **ou**, e depois um código com os exemplos:

| Valor 1| Valor 2 | Operação| Resultado|
|:-------------:|:-----------------:|:-------------:|:-------------:|
| Verdadeiro    | Verdadeiro    | E| VERDADEIRO|
| Verdadeiro    | Verdadeiro    | OU| VERDADEIRO|
| Verdadeiro|      Falso     | E| FALSO|
| Verdadeiro|      Falso     | OU| VERDADEIRO|
| Falso|      Falso     | E          | FALSO|
| Falso|      Falso     | OU         | FALSO|
| Falso|      Verdadeiro   | E           | FALSO|
| Falso|      Verdadeiro   | OU          | VERDADEIRO|

```javascript
    let a = 2;
    let b = 3;
    let c = 6;
    let d = 5;
    let aMaiorQueB = a>b;
    let cMaiorQueD = c>d;
    let bMaiorOuIgualAD = b>=d;
    let dMenorQueA = d<a;
    console.log('a  >  b  E   c  >  d ?   '+( aMaiorQueB && cMaiorQueD ));
    console.log('a  >  b  OU  c  >  d ?   '+( aMaiorQueB || cMaiorQueD ));
    console.log('b  >= d  E   d  <  a ?   '+( bMaiorOuIgualAD && dMenorQueA));
    console.log('b  >= d  OU  d  <  a ?   '+( bMaiorOuIgualAD || dMenorQueA));
    console.log('Se inverter  a  >  b ?   '+ (!aMaiorQueB));
```

Usem outros valores para nossas variáveis e vejam o resultado!

Na próxima vamos ver o que podemos fazer com isso aí!