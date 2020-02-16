---
layout: post
title:  "Git + Latex"
date:   2020-02-15 21:34:00 -0300
categories: tutorial
mathjax: true
---
* TOC
{:toc}

[Git download][download-git]
## Glossário
-commit: tira uma foto

## Fluxo básico
1. Criar um repositório
2. Alterar arquivos
3. Commitar
4. Pull

{%highlight GitHub %}
git init  
{%endhighlight%}

##Criar um novo repositório
## Configurar o username para todo repositório no computador
1. Abra o Git Bash (terminal)
2. Configure o Git username:
{% highlight Git %}
$ git config --global user.name "Mr Robot"
{% endhighlight %}
3. Confirme que você configurou o Git username corretamente:
{% highlight Git %}
$ git config --global user.name
> Mr Robot
{% endhighlight %}

[download-git]: https://git-scm.com/download
