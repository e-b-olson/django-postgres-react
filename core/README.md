# django+postgres+react  
## core
Very basic starter project for django + postgres + react with docker.

> **Note**  
>  
> `core` contains the most basic django + postgres + react container specification.  
> If you want something more *out-of-the-box*, please checkout the `sample_project` directory.

### Getting Started

You will need to have Docker and Docker Compose installed in order to run this project in a container.

###### First, you'll want to be in the `core` directory

`$ cd core`  

###### Now, build the container

`$ docker-compose build`

###### Then run the app:

`$ docker-compose up`

###### Check to see if it worked.

Open a web browser and navigate to `http://localhost:3000`.  You should see the `Success!` page.  
  
### Next Steps   
Make it your own! 

(1) Update the docker-compose file  
> **Note**  
> Search the files for all the `TODO:` tags and make the necessary changes
  
(2) Create a django project in your new container:  
  
`$ sudo docker-compose run api django-admin startproject your_project_name_here .`  
  
> **Warning**  
>  
> If you are running on Linux, you may need to update your file ownership:  
> `$ sudo chown -R $USER:$USER your_project_name_here manage.py`  
  

(3) Update Project Settings  
  
At this point, you will most likely need to update your django project's `settings.py` file to do things like: set the allowed hosts, add database connection information, etc.  If that all sounds too complicated, consider using the [`sample_project`](https://github.com/e-b-olson/django-postgres-react/tree/main/sample_project) instead!
  
  
> Special Thanks to docker for their excellent [documentation](https://docs.docker.com/samples/django/)!
