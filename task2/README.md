docker build -t django-task .  

docker run --name django-task-container -p 8000:8000 -d django-task
