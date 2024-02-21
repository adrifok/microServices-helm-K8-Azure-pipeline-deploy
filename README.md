I get the development code from IBM Instana project that they kindly provide for free. 
In this case its an E-commerce named Robot Shop. 
This is a three tier architecture project that contains 8 microservices developed with Java, 
Node.js,Go, Python and PHP.
It also contains 2 databases (mySQL,MongoDB) and Redis involved as in memory data store.
I create the complete pipeline to deploy: 

-Creation of Azure virtual machine 
-Docker images of every microservices with Docker Compose 
-Helm yaml file as package manager for Kubernetes
-Deployment into AKS Kubernetes containers Ingress controller 
-Exposure of the project to end users.




