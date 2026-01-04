FROM python:3.14.2

RUN virtualenv venv

ENTRYPOINT bin/bash

RUN /bin/bash -c "source venv/bin/activate"

RUN pip install apache-beam[gcp]
