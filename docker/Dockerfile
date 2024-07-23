FROM python:3.10.14-bookworm

WORKDIR /app

COPY src/airflow_project/scripts/* .
RUN chmod 777 /app/entrypoint.sh

ENTRYPOINT ["/app/entrypoint.sh"]