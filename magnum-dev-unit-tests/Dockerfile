FROM ubuntu:xenial

RUN apt-get update && \
    apt-get install -y python-dev libssl-dev libxml2-dev curl \
                       libmysqlclient-dev libxslt-dev libpq-dev git \
                       libffi-dev gettext build-essential python3.5-dev \
                       python-pip

RUN pip install -U pip
RUN pip install virtualenv flake8 tox testrepository git-review
RUN pip install -U virtualenv
