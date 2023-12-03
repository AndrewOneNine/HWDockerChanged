FROM python:latest
WORKDIR /django_task
COPY ./ /django_task
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
