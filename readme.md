```
# Alura ForumHub API 

## Descrição

Este projeto é uma API REST para um fórum online, desenvolvido como parte do Challenge Back-End da Alura. A API, nomeada "FórumHub", é construída utilizando Spring Boot e permite a gestão de tópicos com operações CRUD completas.

## Funcionalidades

- **Criação de Tópicos:** Permite aos usuários criar novos tópicos de discussão no fórum.
- **Listagem de Tópicos:** Os usuários podem visualizar uma lista de todos os tópicos existentes.
- **Busca de Tópicos:** A API permite recuperar um tópico específico usando seu ID.
- **Atualização de Tópicos:**  Os usuários autorizados podem modificar informações em tópicos existentes.
- **Exclusão de Tópicos:** Tópicos podem ser removidos do fórum, mediante autorização.

## Tecnologias Utilizadas

- Java 
- Spring Boot
- Spring Data JPA
- Spring Security
- Flyway (Migrações de Banco de Dados)
- Banco de Dados Relacional (ex: MySQL, PostgreSQL)
- JWT (JSON Web Token) -  Autenticação e Autorização

## Como executar o projeto

1. **Pré-requisitos:**
   - Certifique-se de ter o Java JDK instalado (a versão recomendada está no arquivo `pom.xml`).
   - Tenha o Spring Framework e um banco de dados relacional (como MySQL ou PostgreSQL) configurados em sua máquina.
   
2. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/alura_forumHub.git
   ```

3. **Configurar o Banco de Dados:**
   - Atualize as configurações do banco de dados no arquivo `application.properties` dentro da pasta `src/main/resources`.

4. **Executar a Aplicação:**
   - Navegue até o diretório raiz do projeto e execute o comando:
     ```bash
     ./mvnw spring-boot:run
     ```

## Próximos Passos

- Implementar funcionalidades para gerenciar respostas aos tópicos.
- Integrar com um sistema de notificações para avisar os usuários sobre novas respostas.
- Criar uma interface de usuário para interagir com a API.


## Contribuindo

Sinta-se à vontade para contribuir com este projeto!  Você pode abrir issues para reportar bugs, sugerir melhorias ou enviar pull requests.

---


