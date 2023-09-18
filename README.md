# SparkStandAlone

Este repositório possui a finalidade de ser um material de estudo, desenvolvendo um cluster do spark de uma forma simples 

## Como Usar

- Clone o repositório:
    - git clone https://github.com/victor-s-santos/SparkStandAlone

- Build a imagem:
    - docker-compose up --build

-----------------------------------

Desta forma, será criado um cluster Spark standalone de um único host. Os seguintes nodes serão criados, e podem ser acessados como segue abaixo:

Component | URL
---|---
Master | http://localhost:8080/
Worker | http://localhost:8081/
History server | http://localhost:18080/
Jupyter notebook server | http://localhost:8888/

Então, acessando o endereço reference a `Jupyter notebook server`, podemos criar os notebooks para usar o spark. 