---
layout: post
title:  "Algoritmos"
date:   2019-02-13 08:30:00 -0300
categories: introdução
tags: none
image: /assets/article_images/2019-02-04-ola-mundo/desktop.JPG
---

No capítulo anterior, vimos o que são algoritmos, e mencionei no final sobre variáveis.

Em programação, variáveis são elementos no código onde é possível armazenar valores.

Um exemplo simples:

<pre>
    variavel x = 148
    variavel y = 200
    variavel z = x + y
</pre>

Estou armazenando 148 na variável x e 200 na y. qual seria o valor de z?

Já podemos começar a rascunhar alguma coisa em código real: Vá [neste link](https://repl.it/languages/javascript). Este site cria um ambiente em que será possível executar códigos em javascript e obter o resultado no painel do lado, que chamamos de console. Eu uso bastante para testar trechos de código. Vamos pegar aquele algoritmo acima e fazer no javascript, só acrescentando uma exibição no console dos valores:

```javascript
    let x = 148
    let y = 200
    let z = x + y
    console.log(z)
```

Aproveite para modificar o código, os valores e operações aritiméticas:

```javascript
    let x = 148
    let y = 200
    let soma = x + y
    let subtracao = x - y
    let multiplicacao = x * y
    let divisao = x / y
```

Variáveis não são somente numéricas: podemos também ter valores em texto. No javascript podemos usar aspas simples para identificar, e o sinal de + para unir (o que chamamos de concatenar). Exemplo:

```javascript
    let x = 'texto'
    let y = 'unindo'
    console.log('estou ' + y + ' informações de ' + x + '!')
```

Podemos ver mais formas de juntar strings e de realizar operações aritméticas mais pra frente!