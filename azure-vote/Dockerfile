FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN apt update ;  apt upgrade --yes
RUN pip install redis
RUN pip install django==3.0
ADD /azure-vote /app
