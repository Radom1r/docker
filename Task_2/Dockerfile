FROM python:3.11

WORKDIR src
COPY . .
RUN pip install -r requirements.txt
ENV MY_ENV=venv
EXPOSE 2006
CMD ["python", "-u", "manage.py", "--host", "0:0:0:0", "--port", "2006"]