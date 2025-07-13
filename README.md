# Sistema de E-commerce

Este projeto descreve a modelagem de um sistema de E-commerce, utilizando um diagrama de classes elaborado com base nos principais elementos necessários para realizar compras online, desde o cadastro do usuário até a finalização do pagamento.

## 📄 Descrição

O sistema foi projetado para simular o funcionamento básico de uma loja virtual, com funcionalidades como:

- Cadastro de usuários
- Gerenciamento de produtos
- Carrinho de compras
- Processamento de pedidos
- Controle de pagamentos

## 🧩 Estrutura de Classes

O diagrama de classes incluído no arquivo `Ecommerce.drawio.pdf` contém os seguintes elementos:

### 📌 Usuario
- **Atributos:** CPF, nome, email, senha
- **Métodos:** Inserir senha, endereço, forma de pagamento

### 📌 Produto
- **Atributos:** ID, nota, nome do usuário, comentários, forma de pagamento, usuário
- **Métodos:** Informar ID, buscar CPF do vendedor, receber forma de pagamento

### 📌 Pedido
- **Atributos:** Identificador, nome, data, nota fiscal
- **Métodos:** Informar identificador, receber endereço e forma de pagamento, mostrar nota fiscal

### 📌 Pagamento
- **Atributos:** Forma de pagamento, desconto, data
- **Métodos:** Informar forma de pagamento, aplicar desconto, informar data do pagamento

### 📌 Carrinho de Compras
- **Atributos:** Quantidade de pedidos, valor dos produtos, data
- **Métodos:** Informar quantidade de produtos, verificar desconto, informar valores, remover produtos

## 🛠️ Arquivo do Diagrama

O arquivo `Ecommerce.drawio.pdf` representa visualmente a estrutura do sistema em UML. Para edição mais direta, recomenda-se utilizar a versão `.drawio` no [draw.io](https://draw.io):

1. Acesse o site
2. Importe a versão editável do arquivo (caso disponível)
3. Visualize e edite os relacionamentos e atributos

## 🚀 Tecnologias Sugeridas

Para implementar o sistema, estas tecnologias podem ser consideradas:

- **Backend:** Node.js / Django / Spring Boot
- **Frontend:** React / Angular / Vue.js
- **Banco de Dados:** PostgreSQL / MongoDB / MySQL
- **Autenticação:** JWT / OAuth
- **Pagamentos:** APIs como Stripe ou PayPal

## 👨‍💻 Colaboradores

- Nome do autor: *[Seu Nome Aqui]*  
- Instituição: *[Nome da escola ou curso]*  
- Tipo de projeto: Acadêmico ou pessoal

## 📋 Licença

Este projeto é de uso educacional. Fique à vontade para adaptar, reutilizar ou expandir conforme suas necessidades.

---

