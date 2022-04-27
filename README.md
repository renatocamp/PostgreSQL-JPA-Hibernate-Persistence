# PostgreSQL-JPA-Hibernate-Persistence

## Arquivo de configuração de persistência de dados

É a partir deste arquivo que configuramos o gerenciador de banco de dados. Desta forma,
possibilitamos o uso do Java Persistence API (JPA) em nosso projeto.

## Quais as propriedades a serem configurados na persistência de dados?

### CONFIGURANDO O ARQUIVO PERSISTÊNCE.XML

A primeira tag é a “provider” que compreende um provedor de banco de dados. Ela fornece um EntityManager para a unidade de persistência. Isto é, o “provider” é uma classe que nos permite trabalhar com todas as operações de banco de dados

<provider>org.hibernate.ejb.HibernatePersistence</provider>

### DEFININDO AS PROPRIEDADES DE CONFIGURAÇÃO
A próxima etapa de configuração refere-se a configuração das propriedades, são elas que proverão de fato a conexão/acesso ao banco de dados.

<property name=”javax.érsistence.jdbc.url” value=”jdbc.postgresql://localhost:5432/meuprimeiroprojetojsf” />
<property=”javax.persistence.jdbc.user” value="postgres” />
<property="javax.persistence.jdbc.password" value="admin"/>

### CRIANDO O BANCO DE DADOS




