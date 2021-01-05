FROM python:latest
ARG app_folder=/usr/src/app
ENV script_name=app.py
WORKDIR ${app_folder}
COPY ./code/${script_name} ./
CMD python3 ${script_name}