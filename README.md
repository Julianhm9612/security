# security
Security service for sryap's systems

## Tutorial
https://www.bezkoder.com/spring-boot-security-login-jwt/

## Commands

    mvn install

    mvn spring-boot:run


## H2 config

    http://localhost:8080/h2-ui


## Initial inserts

    INSERT INTO roles(name) VALUES('ROLE_USER');
    INSERT INTO roles(name) VALUES('ROLE_MODERATOR');
    INSERT INTO roles(name) VALUES('ROLE_ADMIN');

