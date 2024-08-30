# Implementation of a Product API
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/luanguedes7/Product-API-APIRestful/blob/main/LICENSE) 

# About the project

This is a back-end application designed to practice API RESTful concepts with Spring Boot and JPA/Hibernate. To this end, I chose to develop a simple product API following Richardson's Maturity Model, consisting of four levels to achieve a RESTFul API.

## API RestFul Model following Richardson's Maturity Model

According to Roy Fielding, one of the creators of the REST architectural model, for an API to be considered RESTful it must follow a set of constraints (rules) predefined by Roy himself. Due to its level of complexity, this model often becomes unattainable. Because of this, Leonard Richardson, a pioneer in defining standards for RESTful APIs, defined a model to achieve an API considered RESTful. To this end, he established four levels, the principles of which include:

(1) URL patterns: URLs must follow a consistent and intuitive pattern to clearly identify resources.

(2) Individual resources: Each resource must be identified by a unique URL, representing a specific entity or object.

(3) HTTP verbs: HTTP verbs, such as GET, POST, PUT and DELETE, must be used according to the actions being performed on the resources.

(4) HATEOAS: The HATEOAS (Hypertext as the Engine of Application State) principle allows clients to navigate the API dynamically, using links provided in resources to discover and access related resources. Example:

Below is an example of the format for loading data in GET in JSON format.

![APIRESTful model](https://github.com/luanguedes7/Product-API-APIRestful/blob/main/assets/APIRESTfulModel.png)


# Technologies used
## Back-end
- Java 17
- Spring Boot 3
- Spring Validation
- Spring Hateoas
- JPA / Hibernate
- Maven

# How to run the project

## Back-end
Requirements: Java 17

```bash
# Clone repository
git clone https://github.com/luanguedes7/Product-API-APIRestful.git

# Enter the back-end project folder
cd backend

# Run the project
./mvnw spring-boot:run
```

# Author
Luan Guedes

https://www.linkedin.com/in/luan-cr%C3%ADsley/
