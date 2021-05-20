FROM python:3.9.2

RUN pip install mlflow==1.17.0 mysqlclient

RUN mkdir /mlflow/

CMD mlflow server \
    --backend-store-uri mysql://mlflow_user:vzuLboFdNSxr4h@mysql:3306/mlflow \
    --default-artifact-root /mlflow \
    --host 0.0.0.0