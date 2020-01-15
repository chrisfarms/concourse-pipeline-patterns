ARG BASE_IMAGE="python:3"
FROM ${BASE_IMAGE}

RUN pip install flask flask_restful

ADD app.py /bin/

EXPOSE 3333

ENTRYPOINT ["/bin/app.py"]
CMD []
