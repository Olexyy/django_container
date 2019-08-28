## Docker based django project.

to run project 
`docker-compose up`
to apply migrations run 
`docker-compose exec web python manage.py migrate`
project should be available at 
`http://localhost:8000`
after migrations are done admin should be available 
`http://localhost:8000/admin/login/?next=/admin/`

## Info:
https://docs.docker.com/compose/django/
https://docs.docker.com/engine/reference/commandline/exec/
https://docs.docker.com/compose/reference/exec/