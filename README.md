# Secure Spring Rest API with Spring Boot 3


## Description
This application demonstrates how to secure a REST API using Spring Boot 3 and Spring Security. It covers the configuration and setup required to protect your endpoints and manage authentication and authorization.

## Features

- **Spring Boot 3 setup** 
- **Spring Security configuration**
- **Basic Authentication and JWT (JSON Web Token) support**
- **Role-based access control**
- **Custom login and access denied handling**


## Requirements

- Java 17
- Maven 3.6.0 ou plus récent
- MySQL ou tout autre base de données relationnelle supportée par Spring Data JPA

## Installation

1. Clonez le repository :


2. Configurez la base de données dans `src/main/resources/application.properties` :

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/votre_db
    spring.datasource.username=your_db_user
    spring.datasource.password=your_db_password

    spring.jpa.hibernate.ddl-auto=update
    ```

3. Compilez et démarrez l'application :

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

 
## Technologies

- Java 17
- Spring Boot
- Spring Security
- MySQL

## Contribuer

Les contributions sont les bienvenues ! Merci de suivre ces étapes :

1. Fork le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`)
4. Poussez votre branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

## Contact

Mohamed Amine Hammi - eminehammi@gmail.com
