---
layout: ../../layouts/PostLayout.astro
title: "Tutorial"
description: "Aprenda a fazer um post no blog"
author: "Joel"
date: "14 Oct 2022"
banner: "bg-yellow-200"
---

# Como fazer um post

## Índice

- [Introdução](#introdução)
- [Do que você precisa](#do-que-você-precisa)
- [Criando um post](#criando-um-post)
  - [Markdown](#markdown)
  - [Adicionando imagens](#adicionando-imagens)
  - [Frontmatter](#frontmatter)
- [Publicando o post](#publicando-o-post)
- [Conclusão](#conclusão)

## Introdução

Esse blog foi feito usando, entre outras ferramentas e bibliotecas, o [Astro](https://astro.build/), um framework moderno para geração de sites estáticos.

O código fonte está disponível no [GitHub](https://github.com/engsoft-unifei/psimodels) e é por lá que você poderá contribuir adicionando posts, propondo alterações, etc. Esse post, assim como todos os outros, corresponde a um arquivo `.md` (markdown) localizado no path (a partir da raiz do projeto) `src/pages/posts/`. O Astro é responsável por transformar esses arquivos em páginas completas.

Nesse post tutorial, você aprenderá a escrever um post especificamente para esse blog, usando seu editor de texto preferido, markdown e o _git_ (para publicá-lo).

## Do que você precisa

Para escrever e publicar um post, é necessário:

- Um editor de texto que suporte markdown
- Conhecimento básico de markdown
- Conhecimento básico de git
- O git instalado em sua máquina
- Uma conta no Github (para posteriormente fazer um _pull request_)

## Criando um post

Hora de criar um post!

Primeiro, dê um fork no repositório principal e faça o clone do seu fork para sua máquina. Para isso, você pode seguir esse [tutorial](https://docs.github.com/pt/get-started/quickstart/fork-a-repo).

```bash
git clone https://github.com/<SEU USUARIO>/psimodels.git
```

ou

```bash
git clone git@github.com:<SEU USUARIO>/psimodels.git # se você usa chave SSH
```

Em seu editor de texto de preferência, navegue até a pasta `src/pages/posts/` e crie um arquivo com o nome do seu post, por exemplo, `tutorial.md`. O nome do arquivo deve ser o mesmo que o título do post, mas em minúsculo e com hífens no lugar dos espaços.

Escreva seu post usando markdown. Abaixo você poderá encontrar um resumo de como escrever usando a linguagem de marcação.

### Markdown

Markdown é uma linguagem de marcação e é a linguagem usada para escrever esse post. Você pode aprender mais sobre ela [aqui](https://www.markdownguide.org/cheat-sheet/) ou por meio da _cheat sheet_ disponível [aqui](/psimodels/posts/markdown-cheatsheet).

### Adicionando imagens

Você pode adicionar imagens ao seu post, para isso, publique a imagem desejada em algum serviço de hospedagem de imagens, como o [Imgur](https://imgur.com/), para obter um link público. Com o link você pode usar a sintaxe de markdown normalmente para adicionar sua imagem.

![Thumbs up boy](https://media.tenor.com/spSgkqK707kAAAAd/ok-all.gif)

> Gifs também funcionam

### Frontmatter

Frontmatter é uma sintaxe complementar ao markdown que permite adicionar metadados ao seu post. É **obrigatório** que todo post tenha um frontmatter, pois ele contém informações importantes, como o título, a data de publicação, o autor, etc.

Para o seu post, utilize a seguinte template de frontmatter (que deve ser colocada no início do arquivo `.md`):

```markdown
---
layout: ../../layouts/PostLayout.astro
title: "Título aqui"
description: "Descrição curta aqui"
author: "Autores aqui, separados por vírgula"
date: "14 Oct 2022"
banner: "bg-yellow-200"
---
```

O parâmetro `date` deve seguir o formato apresentado no exemplo, ou seja, `DD MMM YYYY`.

Já o parâmetro `banner` corresponde a cor do banner que aparece no topo da página do post. As cores vêm do [TailwindCSS](https://tailwindcss.com/docs/background-color), então você pode escolher qualquer uma das cores disponíveis. Para customizar o banner, basta adicionar o prefixo `bg-` e o nome da cor, por exemplo, `bg-yellow-200` como valor do parâmetro `banner`.

Não altere o valor do parâmetro `layout`, pois ele é responsável por definir o layout da página do post.

## Publicando o post

Você já escreveu seu post, adicionando imagens necessárias e configurando adequadamente o frontmatter. Está na hora de publicá-lo!

Certifique-se de salvar suas alterações.

Feito isso, use o git para fazer o commit das suas alterações para o seu repositório local e, depois, faça o push para o seu repositório remoto (seu fork).

> IMPORTANTE: Tenha certeza de escrever a mensagem de commit incluindo os outros autores do post, caso haja mais de um autor. Caso contrário a contribuição dos demais autores não será reconhecida.

Para incluir co-autores no commit, basta seguir a sintaxe de commit (mais detalhes [aqui](https://docs.github.com/pt/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors)):

```bash
git commit -m "Sua mensagem de commit

Co-authored-by: ApelidoDoGithub email@doGithub.com"
```

> IMPORTANTE: O espaço entre a mensagem de commit e o Co-authored-by é obrigatório. O email do co-autor deve ser o mesmo email da conta do Github do co-autor.

Em seguida, na interface do Github no navegador, vá até o seu fork e clique no botão verde "New pull request". (Em caso de dúvida, siga o [passo a passo](https://docs.github.com/pt/get-started/quickstart/contributing-to-projects#making-a-pull-request)).

Complete o pull request adicionando os detalhes necessários e aguarde a revisão do seu post. Se tudo estiver ok, seu post será publicado em breve!

## Conclusão

Agora você já sabe como escrever um post para o Collab. Espero que tenha gostado e que continue contribuindo com o projeto!
