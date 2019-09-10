# Recruta Tech - DevOPS and IA
### Demo project

[![Maintainability](https://api.codeclimate.com/v1/badges/2986fab3b5feab31c0c5/maintainability)](https://codeclimate.com/github/joepreludian/recrutatech_devops_ia/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/2986fab3b5feab31c0c5/test_coverage)](https://codeclimate.com/github/joepreludian/recrutatech_devops_ia/test_coverage)
[![Build Status](https://travis-ci.org/joepreludian/recrutatech_devops_ia.svg?branch=master)](https://travis-ci.org/joepreludian/recrutatech_devops_ia)

This project aims to show a couple of things;
* How DevOps can leverage tooling of your application;
* How to test and see coverage statistics;
* How to handle deployables;
* How to generate deployables;
* How to handle semantic versioning;

## How to develop
This project is built upon `docker` and `docker-composer`. The compose container adds a built in jupyter notebook listening on port 8888;
[](https://docs.pipenv.org/en/latest/)

    $ make setup  # Runs the docker-compose up
    $ make pip  # Install all dependencies of pipenv

After you will be able to point your browser to `http://localhost:8888` and you will be able to see the jupyter notebook;

    $ make app  # Runs the app.py command

This command will run, loads the database of 156;
Running tests:

    $ make test

## Running a shell inside container

    $ make shell

## Contribute
Just fork it, develop and then provide me an PR.

## Useful Links

* https://resources.github.com/downloads/development-workflows-data-scientists.pdf;
* https://cdn2.hubspot.net/hubfs/532045/DataOps-an-Agile-Methodology-for-Data-Driven-Organizations-White-Paper-DataScience.com.pdf;
* https://medium.com/airbnb-engineering/scaling-knowledge-at-airbnb-875d73eff091;
* https://cdn2.hubspot.net/hubfs/532045/oracle-ds-roadmap-worksheet.pdf;
* https://interact.f5.com/rs/653-SMC-783/images/F5%20State%20of%20App%20Delivery%20Report%202017.pdf;
* https://medium.com/faun/devops-without-devops-tools-3f1deb451b1c;
* https://medium.com/experience-valley/utilizando-o-elk-stack-em-um-app-rails-como-ferramenta-de-business-intelligence-5e6ebe029422;
* http://slides.com/jonhnathatrigueiro/docker#/;
* 
