# Work Shop
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

# Sobre o projeto

Este **workshop** é um projeto desenvolvido em **Spring Boot** durante meus estudos pessoais, por meio do curso **Java COMPLETO: Programação Orientada a Objetos, UML, JDBC, Spring Boot, JPA, Hibernate e MySQL**.

A aplicação consiste em um sistema de gerenciamento de pedidos, utilizando o banco de dados **H2**. A estrutura do projeto é composta por entidades como **Categoria**, **Pedido**, **Item de Pedido**, **Produto**, **Pagamento** e **Usuário**. 

A relação entre essas entidades pode ser resumida da seguinte forma:

- O **Usuário** realiza um **Pedido**.
- Um **Pedido** contém um **Pagamento** e está associado a um ou mais **Produtos**.
- A ligação entre **Produto** e **Pedido** é feita por meio do **Item de Pedido**.
- Cada **Produto** pertence a uma ou mais **Categorias**.

## Modelo conceitual
![Modelo Conceitual](https://github.com/Duduzzinxxz/assets/blob/main/Modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- Postman

## Implantação em produção
- Banco de dados: H2

# Como executar o projeto

### Pré-requisitos
- Java 11, 17 ou 21

---
### Passos para Configurar e Executar o Projeto

1. **Clonar o Repositório**  
   Primeiro, clone o repositório do projeto usando o comando abaixo:  
   ```bash
   git clone https://github.com/Duduzzinxxz/workshopp.git
   ```

2. **Acessar a Pasta do Projeto**  
   Entre na pasta do projeto chamada `study`:  
   ```bash
   cd study
   ```

3. **Executar o Projeto**  
   Para rodar a aplicação, utilize o seguinte comando:  
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Acessar o Banco de Dados H2**  
   Abra o navegador e, na barra de pesquisa, digite:  
   ```
   localhost:8080/h2-console/
   ```

5. **Fazer Login no Banco de Dados**  
   Na tela de login do H2, insira os seguintes dados:  
   - **JDBC URL:** `jdbc:h2:mem:testdb`  
   - **User Name:** `sa`  
   - **Password:** (deixe em branco)  

   Clique em **Connect** para acessar o banco de dados.

---

# Autor

Eduardo Benjamin Mattos Aguiar

https://www.linkedin.com........
