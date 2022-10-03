# django+postgres+react  
## Sample Project
Very basic starter project for django + postgres + react with docker.

> **Note**  
>  
> `sample_project` contains a sample django project (with settings file and postgres connection).  

### Getting Started

You will need to have Docker and Docker Compose installed in order to run this project in a container.

###### First, you'll want to be in the `sample_project` directory

`$ cd sample_project`  

###### Now, build the container

`$ docker-compose build`

###### Then run the app:

`$ docker-compose up`

###### Check to see if it worked.

Open a web browser and navigate to `http://localhost:3000`.  You should see the `Success!` page.    
Open another tab and navigate to `http://localhost:8000`.  You should see the django `Congratulations!` page.  
  
### Next Steps   
Make it your own!   
* Search the files for all the `TODO:` tags in the code and make the necessary changes -or-  
* Create a new django project to start from scratch, keeping the SampleProject for reference  
(see the [`core` README](https://github.com/e-b-olson/django-postgres-react/tree/main/core) for more info on creating a new django project in the container)
