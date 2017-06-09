# Desafio de contratação - Desenvolvedor Web

O desafio é criar um CMS simples em PHP ou Javascript (NodeJS).

O intuito desse desafio é avaliar de forma simples, ou seja, não é necessário criar nada complexo (a não ser que seja seu desejo)

Esse teste pode ser feito por front-ends, back-ends e fullstack developers, leia todo o conteúdo dessa página pra saber as instruções para cada papel mostrado.

## Restrições
 - *Não é permitido o uso de frameworks de CMS ou MVC, apenas bibliotecas*

## Requisitos mínimos do CMS

As seguintes funcionalidades são esperadas na aplicação:

- Sistema de login
- Criação e edição de conteúdos (posts) com os campos:
  - título
  - corpo
  - path (exemplo: /noticias/titulo-do-post
- Visualização do conteúdo
- Listagem de conteúdos
- As páginas criadas devem ser acessíveis pela rota no "path"

## Não faço back-end

Caso você não programe back-end, o desafio será criar apenas os temas do site:

- Homepage (listando os últimos posts)
- Detalhe do post (ilustrar cenários onde há novos campos no conteúdo post)
- Formuĺário de criação e edição do post (ilustrar cenários onde há novos campos no conteúdo post)

Lembrando que não é necessário aplicar nenhum funcionamento no back-end caso você não faça frontend

## Não faço front-end

Caso você não faça front-end, a camada de tema (nem homepage) todos os endpoints devem ser feitos usando endpoints JSON.

## Bônus adicionais

1. Testes de unidade / de integração
2. Utilizar taskrunners
3. Código padronizado
4. Código comentado com explicações
5. Criar Dockerfile correspondente ao projeto
