---
layout: post
title:  "Jekyll e Github Pages"
date:   2013-08-28 11:00:00
categories: jekyll update
---

Quem nunca teve um projeto e precisou criar uma página o explicando melhor ou precisou detalhar uma documentação de como usá-lo? Porém quando pensamos em fazer isso o primeiro pensamento que passa  na nossa cabeça é: Criar um "blog"ou criar um site, e ai começa toda a burocracia: registrar domínio, contratar hospedagem e finalmente criar o site do projeto. Quantos passos eim? Fora o fato de você ainda ter que montar o HTML para que a sua página fique "legal". 

-

E se você pudesse apenas escrever o seu texto com algumas marcações e alguém gerar todo o HTML pra você? E melhor, se alguém hospedasse isso gratuitamente pra você?

O que é Jekyll?
---------------

O Jekyll é uma aplicação desenvolvida em __Ruby__, basicamente para que você possa escrever seus textos apenas com alguma linguagem de marcação e então o Jekyll irá gerar um site no estilo de um blog que você pode hospedar aonde você achar interessante.

Começando com o Jekyll
-------------------

Para que você possa começar a usar o Jekyll, você terá que instalar o ruby na sua máquina. Então apenas execute o comando:

__gem install jekyll__

e pronto, o Jekyll está instalado na sua máquina e pronto para usar. 

-

_Para que você possa instalar o jekyll sem maiores problemas é interessante que você esteja usando um sistema operacional Linux, Unix, or Mac OS X, porém existe um meio que a documentação explora de como instalar o jekyll no Windows._

-

Para criar um blog usando o jekyll é bem fácil, é necessário apenas executar: 

__jekyll new NOME DO SEU BLOG__

__jekyll serve__ _Esse comando irá iniciar o servidor do jekyll com o seu blog_

Agora acesse: http://localhost:4000

Pronto, seu primeiro blog está criado.

Criando um novo post
---------------------

Para criar um novo post usando o jekyll, é necessário seguir a convenção do jekyll, todos os seus posts ficam na pasta _posts. Para criar um novo post siga o padrão:

-

YYYY-MM-DD-Titulo-do-Seu-Post.LINGUAGEM DE MARCACAO QUE DESEJAR. _Por exemplo usando Markdown: 2013-08-29-Meu-Primeiro-Post.markdown_

_A linguagem de marcação que estamos utilizando nesse post é uma bem conhecida: Markdown. Você pode encontrar toda a documentação dela [aqui](http://daringfireball.net/projects/markdown/)._

Agora apenas suba o seu servidor de novo, e pronto, seu post está criado.

Simples não?

Integrando Jekyll e Github Pages
--------------------------------

A estrutura do Github Pages utiliza o Jekyll para "renderizar" suas páginas, que coisa não?

-

Então com isso fica bem mais simples para que a gente integrar o nosso blog utilizando Jekyll com o Github Pages. É necessário seguir apenas alguns passos para isso.

-

Existem duas formas de integrar seu blog jekyll com o Github, Primeira, você pode usar o github pages para a sua conta do Github, e também pode usar para um projeto em específico. Os passos para fazer isso é bem simples. 

-

Para criar o seu blog com Jekyll para sua conta, é necessário que você crie um repositório no github com o seguinte nome:

USUARIO.github.io - _No meu caso filipemonteiroth.github.io_

-

Pronto, após isso feito, suba o projeto que você construiu utilizando o Jekyll para a branch master desse projeto, espere alguns minutos e acesse: USUARIO.github.io.... __TCHANRAM__ o Github publicou suas páginas! :D

-

Se você quiser utilizar o Jekyll para um projeto o processo é um pouco diferente. Crie no seu projeto uma branch chamada __gh-pages__ e suba o seu projeto em jekyll lá e prontinho, você então já pode acessar: USUARIO.github.io/Nome do seu Projeto.

-

Simples não? Isso que vimos é apenas a ponta do "Iceberg", o Jekyll é muito mais do que isso, você também pode: usar seu proprio dominio ao invés do github.io, alterar o css dentre muitas outras funciolidades legais. Se quiser se aprofundar mais no Jekyll... Claro o melhor lugar é ir na [documentação](http://jekyllrb.com/docs/home/). Então pessoal, é isso. Se quiserem tirar alguma dúvida dando uma olhada nesse projeto, é só acessar [https://github.com/filipemonteiroth/filipemonteiroth.github.io](https://github.com/filipemonteiroth/filipemonteiroth.github.io).

-

Aguardem o próximo Post da JavaCE

-

__Configurando seus projetos utilizando Gradle__
