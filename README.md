# :computer: Projeto DSList

## Sobre o projeto
Uma aplicação backend que tem como proposta ser uma pesquisa de games, onde os usuários podem realizar buscas com base no gênero e classificação dos jogos, e assim encontrar informações sobre seus títulos favoritos.

## Modelo de Domínio DSList

![Modelo de domínio DSList](https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png)

## Como executar o projeto?
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

- `GET Games` - Busca por todos os jogos;
- `GET Games by id` - Busca um jogo pelo id;
- `GET Game lists` - Busca as categorias de jogos;
- `GET Game by lists` - Busca os jogas da categoria pelo pelo id da lista;
- `POST Lists replacement` - Permite o usuário organizar a lista da maneira que preferir.

## Conecte-se Comigo

Carlos Costa

https://www.linkedin.com/in/carlossilvacosta/
