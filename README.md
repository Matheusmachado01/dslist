# Project Spring DsList




**Project Spring DsList** é um sistema Backend onde a API desenvolvida implementa um modelo de dados onde irá executar consultas SQL. 
É um sistema de coleção de jogos se chama DsList, está lista de jogos é separada em 2 coleções uma de aventura e a outra de RPG. O sistema também 
possui uma funcionalidade de mudar os jogos de posições.



## Temas Abordados  :

Sistema web e recursos | Cliente/servidor, HTTP, JSON |
Padrão Rest para API web  |
Estruturação de projeto Spring Rest |
Entidades e ORM  |
Database seeding  |
Padrão de camadas  |
Controller, service, repository  |
Padrçao DTO  |
Relacionamento N-N  |
Classe de associação, embedded id  |
Consultas SQL no Spring Data JPA  |
Projections  |
Ambiente local com Docker Compose  |
Processo de homologação local  |
Processo de deploy com CI/CD  |
Configuração CORS  |
Design e implementação de endpoint  |
Verbo HTTP e indepotência  |
Linguagem java  freamework Springboot  |

## Tecnologias utilizadas

## Back end
- Java JDK 17
- Spring Boot
- PostgreSQL
- Maven
- Postman
- VS Code
-- railway.app
  
DEPENDÊNCIAS | REFERÊNCIA
------------ | ---------------
SPRING WEB   | https://mvnrepository.com/artifact/org.springframework/spring-web/3.0.8
SPRING SECURITY  | https://mvnrepository.com/artifact/org.springframework.security/spring-security-core/5.7.3
SPRING DATA JPA          | https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-data-jpa/3.0.8
DEV TOOLS    | https://spring.io/blog/2015/06/17/devtools-in-spring-boot-1-3
H2 DATABASE  | https://mvnrepository.com/artifact/com.h2database/h2

## Implantação em produção
- Back end: Springboot
- railway.app
- Banco de dados: H2 Database
- Git

```bash
# clonar repositório
git clone https://github.com/Matheusmachado01/dslist

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```



