FROM python:3.10.11-bullseye
ENV PYTHONUNBUFFERED 1
WORKDIR /smartsanthe
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . .
#CMD ["python", "manage.py", "collectstatic"]

ENTRYPOINT ["sh", "/entrypoint.sh"]