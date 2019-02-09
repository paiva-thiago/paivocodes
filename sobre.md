---
layout: page
title: Sobre
permalink: /sobre/

---
  {% assign month = site.time | date: '%m' %}
  {% assign month = month | times:1 %}
  {% assign now = site.time | date: '%Y' %}
  {% assign birth = 1986 %}
  {% assign work = 2005 | times:1 %}
  {% assign now = now | times:1 %}
  {% assign birth = birth | times:1 %}
  {% assign age = now | minus: birth %}
  {% if month<11 %}
  {%      assign age = age | minus:1 %}
  {%   endif %}
  {% assign work = now | minus:work %}

Olá pessoal! :)

Meu nome é Thiago Paiva. dos meus {{ age }} anos, {{ work }} foram profissionalmente dedicados à programação.  

Antes de iniciar minha faculdade (Tecnologia em Processamento de Dados - FATEC - Santos) - Sim, estou velho, Análise e Desenvolvimento de Sistemas tinha esse nome, rs - cheguei a fazer um curso técnico que não foi concluído por um misto de relaxo com aquele tempero de burocracia. Mas neste período comecei a tentar criar páginas, a fuçar nos agora jurássicos Frontpage e Dreamweaver. Cheguei até a fazer sites pra bandas de amigos - e pra minha própria banda também. Tempos em que Geocities e HPG reinavam nas hospedagens gratuitas.

Durante minha faculdade consegui um estágio na cidade em que eu morava, em Cubatão - onde comecei minha jornada profissional em programação. Cuidava de um sistema Desktop em Delphi e cuidava de um portal web em PHP, responsável por consultas de extratos e pedidos de créditos de cartões de benefícios PAT. Sabe esse seu Vale Alimentação ou Vale Refeição? São benefícios PAT.

Me efetivei nesta empresa, esta empresa mudou pra Santos, e aconteceu muita coisa neste meio tempo - inclusive cogitei sair da área de Tecnologia da Informação, montando uma estratégia toda para sair gradativamente da informática para comunicação fazendo uma pós em arte e tecnologia (Especialização em Estéticas Tecnológicas) na PUC de São Paulo. Me rendeu pesquisas bem bacanas em músicas e redes sociais, me fez conhecer um mundo de estudos culturais que tenho saudade e até vontade de voltar.

Em 2015 comecei a lecionar como professor substituto nos cursos superiores de Análise e Desenvolvimento de Sistemas e no Técnico Integrado ao Médio em Informática no IFSP - Campus Cubatão. Mal sabia que este terreno iria me transformar profissionalmente e recuperar meu gosto por informática, aliando a educação! Tamanho gosto que em 2016 comecei a lecionar também na Etec e saio da empresa onde estive por quase 11 anos!

2016 encerra, contratos idem e começo 2017 trabalhando em São Paulo como Analista Programador na Meta, alocado na equipe de sustentação da Porto Seguro. Este ritmo de identificação de problemas, correção de códigos alheios e publicações em produção encerram no início do ano seguinte - em que surge uma convocação de um concurso feito em 2014 - quando passo a ser Analista de Sistemas Sênior da Prefeitura de São Bernardo do Campo.

Porém, aquele legado que tive quando saí do mundo da educação não morreu. Meu desejo de manter um blog abrigando tutoriais das tecnologias que gosto e domino ainda estava vivo, só meu bloqueio criativo e aquela falta de organização estavam impedindo o surgimento. Mas comecei 2019 determinado a tirar isto do papel, e este blog começa assim!

Certeza de que aprenderemos muito (não são só vocês que aprendem!) programação, frameworks e afins!
