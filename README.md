# django-postgres-react
Very basic starter project for django + postgres + react with docker.

> **Note**  
>  
> `core` contains the most basic container configuration for django + postgres + react.  
>  
> `sample_project` contains `core` + a sample django project (with settings file and postgres connection).  

## Getting Started

You will need to have Docker and Docker Compose installed in order to run this project in a container.

###### First, select to use either `core` or `sample_project`  

`$ cd core`  -or-  
`$ cd sample_project`  

###### Then build the container

`$ docker-compose build`

###### Now, start the database service:

`$ docker-compose up db`  

> **Note**  
>  
> You must wait for the database service to complete it's start-up ssequence before moving on to the next step.  

###### Finally, start the other services (django & frontend):  
  
`$ docker-compose up`  

###### Check to see if it worked.

Open a web browser and navigate to `http://localhost:3000`.  You should see the `Success!` page.  

## Sample Project  
If you chose to use the `sample_project`, you can also check to see if django is running:  
  
Open a web browser and navigate to `http://localhost:8000`.  You should see the django `Congratulations!` page.  
