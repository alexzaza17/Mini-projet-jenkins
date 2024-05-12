# Fankem

## Alex

### Eazytraining 18th DevOps Bootcamp

#### Period: march-april-may

Application

Il est question ici pour nous de mettre en place un pipeline qui nous permettra de deployer et d heberger notre server de site web (nginx) dans une plateforme d'hebergement des applications. Nous avons d'abord ecrit le Dockerfile du code html. Creer les jobs qui nous permettrons de reaiser celle ci

Plan de travail

Nous allons realiser ses differents jobs sur Gitlab CI/CD qui permettrons de mettre en place notre pipeline: 
Build
Test d'acceptation
Release de l'image(push de l image sur le Dockerhub)
Deploy staging
Depoy prod
Test staging
Test prod

Avant de realiser ces differentes atsks nousavons tout a d abord redige le Dockerfile, ensuite le jenkinsfile(nous avons bien precise que n importe quel agent pour executer notre job) 

![Artifact console_output](https://github.com/alexzaza17/Mini-projet-jenkins/assets/159175882/964bb3d8-4de9-4270-95e9-af8aaf036061)

![Artifact console_output2](https://github.com/alexzaza17/Mini-projet-jenkins/assets/159175882/291e3fdb-8fcc-4248-b6e4-9a8ece3515d3)

![Screenshot 2024-04-14 123524](https://github.com/alexzaza17/Mini-projet-jenkins/assets/159175882/a65a1700-51c1-4a7b-912a-0629b9ad1101)

![staging production1](https://github.com/alexzaza17/Mini-projet-jenkins/assets/159175882/317c07e1-d9f4-4e38-80c8-03b9434fa57c)

Ici nous pouvons constacter que l application a biene ete heberge sur la plateforme Heroku
![Heroku](https://github.com/alexzaza17/Mini-projet-jenkins/assets/159175882/db981a70-af7d-4267-8d7a-e4cb688d34b5)

