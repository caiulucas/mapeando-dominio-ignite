# Gerenciamento de estoque


## Entidades
- Produto
  - estoque
  - nome
  - preco
  - id
  - tamanho
  - cor
  - estoque minimo

- Venda
  - data
  - produtos
  - total

- Notificacao
  - data
  - mensagem
  - email

- Fornecedores
  - id 
  - nome

## Casos de uso
- Historico
  - deve ser possível visualizar o histórico de vendas com base em um período de tempo

- Notificacao
  - deve ser possível enviar notificações para a empresa quando um produto estiver com o estoque abaixo do estoque mínimo
  - deve ser possível enviar notificações ao sistema da empresa quando um produto estiver com o estoque abaixo do estoque mínimo
  - Deve ser possível receber notificações de fornecedores no sistema e por email

- Definir quantidade mínima
  - Deve ser possível definir uma quantidade mínima de estoque para cada produto da empresa
  - Deve ser possível alterar a quantidade mínima de cada produto

- Rastreamento individual do produto
  - Deve ser possível rastrear um produto com base em um identificador único
  - Deve ser possível usar cor e tamanho como filtros de busca para o produto


