# Estudos com Spring Security

Projeto de estudos com Spring Security. Utilizado como base o guia do Spring.
`GETTING STARTED - Securing a Web Application` : <https://spring.io/guides/gs/securing-web/>

## Requisitos

- JDK 1.8 ou mais recente
- Gradle 4+ ou Maven 3.2+ (Neste projeto foi utilizado Maven)

## Rodando a aplicação

Através do Maven:

`mvn spring-boot:run`

ou também é possível através de um JAR. Para isso, primeiramente deve-se rodar o comando do Maven:

`mvn clean package`

em seguida no terminal:

`java -jar target/demo1-0.0.1-SNAPSHOT.jar`

## Usuário e senha

Para autenticar-se na aplicação é necessário utilizar as seguintes credenciais:

`Usuário` : `user`

`Senha` : `secret123`