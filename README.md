

# This is the API for Postman Course

It is a simple version of an API builded with Django and Django Rest Framework
using Docker.


# You can learn how to build APIs here:

- [Curso de API REST](https://platzi.com/clases/api-rest/)
- [Curso de Django](https://platzi.com/clases/django/)
- [Curso Avanzado de Django](https://platzi.com/clases/django-avanzado/)
- [Curso de Fundamentos de Docker](https://platzi.com/clases/docker/)

# How to run this project
- Install Docker and Docker Compose
- Execute `docker-compose up -d`: This command starts a local server with the API running over 8000 port.
- Get inside the docker container executing `docker exec -it postman-course_web_1 bash`
- Run migrations `python managa.py migrate`
- Inside the docker container execute `source admin_info.sh`

# How to use it
Once the development server is running you can access to the [Django Admin](http://localhost:8000/admin/), there you can perform CRUD operations over the resources. 


# What can you do with it?
## ANYTHING YOU WANT 

This code is free, use it, change it, even you can send me pull requests. Maybe a pull requests with some fixtures of Courses and Materials.
