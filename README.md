# Message in a Bottle
[![Build Status](https://app.travis-ci.com/fedehsq/micro_mib.svg?token=sCUbEzotwbjEpdHdvWDb&branch=master)](https://app.travis-ci.com/fedehsq/micro_mib)

This is the main repository of Message in a Bottle application, self project of *Advanced Software Engineering* course, University of Pisa.

## Team info

- The *squad id* is **9**
- The *team leader* is Francesco Kotopulos De Angelis

#### Members

|         Name and Surname       |              Email                  |
| ------------------------------ | ----------------------------------- |
| Federico Bernacca              | f.bernacca@studenti.unipi.it        |
| Paola Petri                    | p.petri1@studenti.unipi.it          |
| Nicolò Pierami                 | n.pierami@studenti.unipi.it         |
| Francesco Kotopulos De Angelis | f.kotopulosdeange@studenti.unipi.it |
| Manfredo Facchini              | m.facchini1@studenti.unipi.it       |

## Description

"**MyMessageInABottle** might seem at first glance
simply like another messaging app, like many others. WRONG.\
MyMessageInABottle is a time capsule where each user can keep messages, safeguard them, and send them only to decide later when
the recipient will be able to open them. Whether it’s at a specific time
on that same day, weeks later, or even years later. What matters is that
the message cannot be changed or deleted. Even if you uninstall the
app. And it will reach its destination. It’s important.\
There are choices
to be made, and you need to take your time."

## Instructions

### Clone the repository

To clone the repository you have to specify the recursive parameter,
in this way:

`git clone --recursive https://github.com/fedehsq/micro_mib`

All the submodules will be fetched from GitHub and they will be
placed inside the project root.

### Add a submodule

If you want to add a microservice (hence a submodule), you
have to run the command:

`git submodule add -b <branchName> <repoURL>`

### Pull the updates from all repositories

If a developer has pushed to <branchName> branch and you want
to pull the updates, you have to run the following command:

`git submodule update --remote`

#### Documentation

If you are not familiar with git submodules or you have some
doubts about it, you can check the git-scm documentation
[here](https://git-scm.com/book/en/v2/Git-Tools-Submodules). 



## Configuration

Each micro-service should have a single configuration file, placed inside the main project root, with the name `<microservice_name>_ms.conf`. An example of this can be found in the project root.



## Development
### From monolith to microservices!

The project structure should be the following:
![Arch](https://github.com/fedehsq/micro_mib/blob/master/split.jpg)





## Build and run

Application is built with docker-compose. To build the environment
you have to run

`docker-compose build`

To startup application you can issue the following command:

`docker-compose run`

#### Application Environment

The default application environment for this application is **production**. 

## Authors

* [Federico Bernacca](https://github.com/fedehsq)

* [Paola Petri](https://github.com/paolapetri)

* [Nicolò Pierami](https://github.com/pieramin)

* [Manfredo Facchini](https://github.com/ManfredoFac)

* [Francesco Kotopulos De Angelis](https://github.com/dookie182)
