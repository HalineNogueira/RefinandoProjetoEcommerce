# Refinando Projeto Ecommerce  

## Descrição  

Este projeto é um modelo conceitual de banco de dados para um sistema de e-commerce. 

O diagrama de entidade-relacionamento (ER) inclui as principais entidades que compõem o sistema e suas relações. 

O objetivo deste projeto é fornecer uma estrutura sólida para gerenciar produtos, pedidos e informações dos clientes de forma eficiente.  

## Entidades  

Projeto disponível no GitHub feito conforme as instruções de como deveria ser feito e adicionado a uma entidade Cliente PJ e Cartão PJ com relacionamento entre ambos, assim também criei uma entidade Cartão PF para relacionar os cartões do cliente a ele. As relações foram feitos de 1 cliente para muitos cartões.



😁 Cliente PF : Representa os clientes pessoas físicas. Contém  informações como nome, CPF, endereço, forma de pagamento.

💳 Cartão PF:Informações sobre os cartões utilizados pelos clientes para realizar pagamentos.

♾️ Relacionamento entre as entidades de 1:*

👨‍💻 Cliente PJ : Representa os clientes pessoas jurídicas. Inclui dados como CNPJ e informações de pagamento.

💳 Cartão PF : Informações sobre os cartões utilizados pelos clientes para realizar pagamentos.

♾️ Relacionamento entre as duas entidades de 1:*

🛍️ Produto : Armazena detalhes sobre os produtos disponíveis para venda, incluindo categoria, descrição e valor.

📦 Pedido : Representa um pedido feito por um cliente, contendo status e informações de entrega. Apliquei dois atributos na entidade pedido com numero de rastreio e status da entrega. 

♾️ Relação de produto por pedido : Liga os produtos aos pedidos realizados, incluindo quantidade. 
