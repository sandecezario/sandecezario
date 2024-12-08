Objetivo
Estruturar o banco de dados para:

Clientes Registradores , diferenciando Pessoa Física e Pessoa Jurídica .
Gerenciar pedidos e suas respectivas entregas com status e código de rastreamento.
Armazenar pagamentos , aceitando várias formas (Pix, Boleto, Cartão).
Controlar produtos , estoque e fornecedores .

Entidades Principais
Cliente : Dados pessoais e tipo (PF/PJ).
Pedido : Informações do pedido realizado.
Pagamento : Tipo de pagamento e referência ao cartão , se aplicável.
Cartão : Informações seguras de cartões utilizados.
Entrega : Status e código de rastreamento do pedido.
Produto : Descrição, categoria e valor dos produtos.
Estoque : Local e quantidade dos produtos armazenados.
Fornecedor : Dados dos fornecedores.
Vendedor Terceirizado : Fornecedores externos que disponibilizam produtos.

Relacionamentos
Cliente → Pedido : Um cliente pode realizar vários pedidos.
Pedido → Pagamento : Um pedido pode ter várias formas de pagamento.
Pagamento → Cartão : Pagamentos com cartões registram detalhes do mesmo.
Pedido → Entrega : Cada pedido tem um status e código de rastreamento.
Produto → Fornecedor / Estoque / Vendedores : Controle detalhado dos produtos.


<!--
**sandecezario/sandecezario** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
