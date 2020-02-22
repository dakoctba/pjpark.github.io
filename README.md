# Blog do projeto PJPark

Para criar um novo post basta salvar um arquivo no diretório ```_posts``` com o padrão ```yyyy-mm-dd-title-with-hyphens.md```

No início do arquivo colocar o cabeçalho

```
---
layout: post
title:  "Título completo"
author: "Nome do autor"
date:   yyyy-mm-dd hh:MM:00 -0300
categories: blog
tags: [contabilidade, empresa-inativa, pt-br]
---
```

O arquivo deve ser escrito usando a notação Markdown (https://guides.github.com/features/mastering-markdown)

## Ambiente de desenvolvimento

Para subir o projeto localmente utilizar o comando ```docker-compose up```

Para atualizar um post utilizar o comando ```docker run jekyll jekyll build```
