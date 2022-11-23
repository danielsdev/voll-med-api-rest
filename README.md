# voll.med API
API REST para gerenciar médicos de um consultório

## Tecnologias
 - Java 17
 - Spring Boot 3.0
 - Maven Project

## Módulos do Spring Boot
- Spring Web
- Validation
- Spring Data JPA
- Driver MySQL
- Flyway
- Lombok

## Criar banco de dados
```bash
docker run --name=tmp_mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD={SECRET_PASSWORD} -e MYSQL_DATABASE=vollmed_api mysql
```
