FROM jupyter/scipy-notebook:python-3.9.2

RUN conda install --quiet --yes \
    'mlflow=1.17.0' \
    'sqlalchemy'
WORKDIR /notebooks