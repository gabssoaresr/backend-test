# Coderockr Investments API

An API for an application that stores and manages people and their investments.

## Initializing

You need to have `docker` and `docker-compose` installed on your machine. for that check the proprietary documentation links: [Docker](https://docs.docker.com/engine/install/) e [Docker-compose](https://docs.docker.com/compose/install/), in that order.

Then you should copy the data from `.env.example` to `.env`.

To install all packages and dependencies, run:

```
make build
```

Or, if you're using windows open the `Makefile` file and run the `build` block, line by line. To know more[leia](makefile).

Access http://localhost:8080 and you will see the service running.

## Link to the API documentation

**There are 2 different documentations**
`Swagger:`
    - With Swagger it's possible to test the endpoints directly from this documentation, it makes testing a lot easier. Access the link **http://localhost:8080**

`Redoc:`
    - Redoc is user-friendly and perfect to use on a daily basis and facilitate API absorption. Access the link **http://localhost:8080/redoc**

## List of third-party libraries used

#### Docker
Docker makes it easy to run the application without having to put in a lot of effort. With application development using Docker, you don’t need to install a bunch of language environments on your system. You can simply run the application inside docker container with the help of a image.

#### Python

Python is an extremely powerful and versatile programming language in terms of the types of applications you can create.

#### Django and Django-RestFramework

Django is a open source framework that is compatible with major operating systems and databases. It has a great number of advantages. It's considered a developer-friendly framework easy to pick up. It provides robust security features, helps to avoid the common mistakes of web development including SQL injection, clickjacking, cross-site request forgery and scripting. 

Django REST framework (DRF) is a open source, mature and well supported Python/Django library that aims at building sophisticated web APIs. It is flexible and fully-featured toolkit with modular and customizable architecture that makes possible development of both simple, turn-key API endpoints and complicated REST constructs.

#### Poetry 

Poetry is a tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you. Poetry offers a lockfile to ensure repeatable installs, and can build your project for distribution.

####  drf_yasg

drf_yasg is a API doc generation tool which provides the option to choose between swagger-ui and redoc or both for generating documentation for your APIs

#### NumPy

NumPy arrays are faster and more compact than Python lists. An array consumes less memory and is convenient to use. NumPy uses much less memory to store data and it provides a mechanism of specifying the data types. **In this case it was used to calculate the difference of months between two dates**

#### Pandas

Pandas is an open-source Python library designed to deal with data analysis and data manipulation. It is built on top of **NumPy** and it has several functions for cleaning, analyzing, and manipulating data, which can help you extract valuable insights about your data set. **In this case it was used to prepare the dates for later calculations.**

#### postgre 

PostgreSQL comes with many features aimed to help developers build applications, administrators to protect data integrity and build fault-tolerant environments, and help you manage your data no matter how big or small the dataset. In addition to being free and open source, PostgreSQL is highly extensible.

