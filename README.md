# :computer: Projeto DSList

## Sobre o projeto
Uma aplicação backend que tem como proposta ser uma pesquisa de games, onde os usuários podem realizar buscas com base no gênero e classificação dos jogos, e assim encontrar informações sobre seus títulos favoritos.

## Modelo de Domínio DSList

![Modelo de domínio DSList](https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png)

## Configurações
Pré-requisitos: Java Version 21

```bash
# clonar repositório
git clone https://github.com/carlossilvacosta/dslist

# executar o projeto
./mvnw spring-boot:run
```
## Tecnologias Utilizadas
- Java;
- Spring Boot;
- JPA / Hibernate;
- Maven;
- Postman;
- Docker;
- Postgresql.

## Rotas

- `GET Games` - Busca a lista de jogos;
- `GET Games by ID` - Busca um jogo por meio do ID;
- `GET Lists` - Busca a categoria das listas de jogos;
- `GET Lists by ID from Games` - Busca a lista categorizado pelo gênero (ID) do jogos;
- `POST Lists Replacement` - Permite o usuário organizar a lista da maneira que preferir.

## Conecte-se Comigo

Carlos Costa

https://www.linkedin.com/in/carlossilvacosta/
