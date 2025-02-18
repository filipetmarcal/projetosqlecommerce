# Modelagem de Banco de Dados para E-commerce

## Descrição do Projeto
Este projeto consiste na modelagem e implementação de um banco de dados para um sistema de e-commerce. A modelagem foi refinada para incluir novas regras de negócio e relações complexas, garantindo um esquema robusto e eficiente.

## Tecnologias Utilizadas
- **MySQL** para modelagem e execução das queries.
- **Workbench** ou **DBDiagram** para criação do modelo conceitual.
- **GitHub** para versionamento do projeto.

## Modelagem do Banco de Dados
A modelagem inclui as seguintes entidades principais:

- **Clientes**: Pode ser Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas não ambos.
- **Pedidos**: Associados a clientes, com status e informações de pagamento.
- **Pagamentos**: Um pedido pode ter mais de uma forma de pagamento.
- **Entregas**: Contém status e código de rastreamento.
- **Produtos**: Associados a fornecedores e estoques.
- **Fornecedores**: Relacionados a produtos.

## Estrutura do Repositório
- `database_schema.sql`: Script SQL para criação do banco de dados.
- `insert_data.sql`: Script para inserção de dados de teste.
- `queries.sql`: Consultas complexas utilizando **JOINs, filtros, ORDER BY, HAVING**, entre outras.
- `README.md`: Documento explicativo do projeto.

## Consultas Implementadas
Algumas das queries incluídas:
- Quantidade de pedidos por cliente.
- Verificação se algum vendedor também é fornecedor.
- Lista de produtos, fornecedores e estoques.
- Relação entre nomes de fornecedores e produtos.

## Como Executar o Projeto
1. Clone este repositório.
2. Execute o script `database_schema.sql` para criar as tabelas.
3. Execute `insert_data.sql` para inserir dados de teste.
4. Utilize `queries.sql` para explorar as informações do banco.

