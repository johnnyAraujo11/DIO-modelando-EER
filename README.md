# DIO-modelando-EER
Modelando um Modelo de Entidade - Relacionamento

O contexto utilizado para a modelagem, segue:

Modelando um projeto de E-commerce no qual um empresa fictícia precisa armazenar informações sobre seus clientes e suas vendas. As entidades envolvidas são:
  - Produto
  - Cliente
  - Pedido
  - Estoque
  - Fornecedor

O cliente pode fazer um ou mais pedidos. Cliente pode cadastra no site utilizando CPF ou CNPJ. Possui endereço de entrega asscociado a um valor de frete. 

Os produtos possui um fornecedor e podem estar presentes em um ou mais pedidos.Pedido pode ser cancelado.

Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;

A modelagem foi feita utilizando o MYSQL Workbench. Segue abaixo o resutado: 
![Desafio](https://github.com/user-attachments/assets/8bb0716d-9f95-4fed-a75c-f5f2c5e4c295)
