# Desafio de contratação - Desenvolvedor Web Front-end

Este é um desafio para testar seus conhecimentos em JavaScript e algum framework de sua preferência (React, Vue, Angular, etc)

Neste desafio existem várias respostas corretas, pois o objetivo é avaliar a sua forma de codificação, e suas habilidades usando a tecnologia escolhida.

## Carrinho de Compras

Seu objetivo é montar um carrinho de compras.

O layout deve ser como de um site de vendas convencional, com uma listagem de produtos e um icone de carrinho de compras no topo do site.

O icone do carrinho de compras deve exibir uma badge com a quantidade de itens presente no carrinho.

### A tela de listagem de produtos deve:

- Listar produtos
  - Ao entrar no site, deve exibir os produtos na listagem com foto, titulo e preço formatado em reais;
  - Ao clicar no produto da lista, deve exibir os detalhes de um produto individual;
- Permitir comprar
  - Ao clicar em comprar, e o produto não estiver no carrinho, deve ser adicionado;
  - Ao clicar em comprar, e o produto ja existir no carrinho, deve ser incrementado em 1;
- Exibir o resumo do carrinho
  - Exibir no icone do carrinho uma badge com quantidade de itens;
  - Exibir ao lado do icone, o valor total da compra;

### O carrinho deve:

- Permitir remover itens;
  - Ao remover, liberar o estoque do produto;
- Permitir alterar a quantidade de um item
  - Ao clicar em aumentar, deve incrementar em 1;
  - Ao clicar em diminuir, deve decrementar em 1;
  - Ao incrementar, deve validar se o produto ainda possui estoque;
  - Ao decrementar, deve liberar o estoque do produto;
  - Não deve permitir o usuário informar quantidade zero;
- Exibir a somatória total dos itens incluídos

## Bônus adicionais

1. Adicionar alguma funcionalidade que você julgue relevante;
2. Utilizar biblioteca gerenciadora de estado (Redux, Vuex, MobX, etc)
3. Testes de unidade / comportamento
4. Código padronizado
5. Versionamento utilizando GIT
6. Código comentado com explicações
