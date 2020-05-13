# k8-crud-webapp
A CRUD app for deployment in K8


This is a simple tutorial for creating a CRUD website using PHP and MySql Database and then deploying it into a K8.
Its a good learning for someone who is looking out to understand the picture from both Dev and an Ops view. 

Below is the tree view of the contents - 

.
├── LICENSE
├── README.md
├── mysql-deployment.yaml
├── mysql-service.yaml
├── webserver.yaml
├── webservice.yaml
└── website
    ├── Dockerfile
    └── src
        ├── common.php
        ├── config.php
        ├── create.php
        ├── css
        │   └── style.css
        ├── data
        │   └── init.sql
        ├── index.php
        ├── install.php
        ├── read.php
        └── templates
            ├── footer.php
            └── header.php



