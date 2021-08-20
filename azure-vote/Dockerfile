FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN apt update ;  apt upgrade --yes
RUN pip install redis
ADD /azure-vote /app
