# SpringBoot-Strategies
Projeto de Spring Boot criado em pós graduação!
 
Objetivo:
- Praticar diversos conceitos do Spring Boot e explorar suas utilizadades.

Desenvolvido:
- API REST com notações do SpringBoot para um objeto de Estudantes.
- Classes de excessões.
- Upload e Download de arquivos.
- Conexão com banco de dados MySQL usando Spring Data JPA.
- Exemplificação de chamadas assíncronas com @EnableAsync.
- Consultas no Banco de Dados com Native Query vs JPQL.
- Agendando uma tarefa com @Scheduled.
- Serviço de Notificação com WebSocket.
- Segurança de requisição à endpoins com Spring Security, Token JWT e auth0.
- Documentação de Api com Swagger.

Dependências:
- Spring Boot 2.7.5 -> pom.xml -> //<version>2.7.5</version>
- Versão Java 11 -> pom.xml ->	<java.version>11</java.version>
- Lombok: responsável por gerar os códigos boilerplate para nós, como Getter e Setters.
- Spring Web: principal dependência para podermos desenvolver nossa aplicação. É composta por outras dependências, entre elas Spring MVC, REST e Tomcat como servidor padrão embutido. Ela já possui todas as configurações necessárias para que possamos rodar e testar nossa aplicação localmente, assim como nossa camada Controller.
- Spring Boot Dev Tools: Permite fazer alterações em nossa aplicação e testar logo em seguida sem precisar parar e rodar a aplicação novamente. Ou seja, ela detecta alterações no código e reinicializa a aplicação automaticamente.
- Spring Data JPA: Simplifica a implementação de repositórios baseados em JPA. Ele oferece funcionalidades para interagir facilmente com bancos de dados usando a API de Persistência Java (JPA)
- MySQL Driver: Para conexão da aplicação ao banco de dados MYSQL.
- SocketIO -> pom.xml: groupId: com.corundumstudio.socketio - artifactId: netty-socketio - version: 1.7.22
- OAuth2 Resource Server: Permite implementação do Spring Security, possibilita utilizar Token JWT para autenticação de rotas e endpoints.
- Swagger -> pom.xml:
         //springfox-swagger2 3.0.0
         //springfox-boot-starter 3.0.0
         //springfox-swagger-ui 3.0.0

==============================================================

Spring Boot project created in the postgraduate course!

Objective:
- Practice various Spring Boot concepts and explore their utilities.

Developed:
- REST API with Spring Boot annotations for a Student object.
- Exception classes.
- File upload and download.
- Connecting to MySQL database using Spring Data JPA.
- Example of asynchronous calls with @EnableAsync.
- Database queries with Native Query vs JPQL.
- Scheduling a task with @Scheduled.
- Notification service with WebSocket.
- Securing endpoint requests with Spring Security, JWT Token, and Auth0.
- API Documentation with Swagger.

Dependencies:
- Spring Boot 2.7.5 -> pom.xml -> //<version>2.7.5</version>
- Java version: 11 ->	pom.xml ->	<java.version>11</java.version>
- Lombok: responsible for generating boilerplate code for us, such as Getters and Setters.
- Spring Web: the main dependency for developing our application. It is composed of other dependencies, including Spring MVC, REST, and Tomcat as the default embedded server. It already has all the necessary configurations for us to run and test our application locally, as well as our Controller layer.
- Spring Boot Dev Tools: Allows making changes to our application and testing them immediately without needing to stop and rerun the application. In other words, it detects changes in the code and automatically restarts the application.
- Spring Data JPA: simplifies the implementation of repositories based on JPA. It offers functionalities to easily interact with databases using the Java Persistence API (JPA).
- MySQL Driver: For connecting the application to the MYSQL database.
- SocketIO -> pom.xml: groupId: com.corundumstudio.socketio - artifactId: netty-socketio - version: 1.7.22
- OAuth2 Resource Server: Enables Spring Security implementation, allowing the use of JWT Tokens for route and endpoint authentication.
- Swagger -> pom.xml:
       //springfox-swagger2 3.0.0
       //springfox-boot-starter 3.0.0
       //springfox-swagger-ui 3.0.0
