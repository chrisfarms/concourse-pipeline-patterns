ARG BASE_DIGEST=3
FROM python:${BASE_DIGEST}

RUN pip install flask flask_restful

ADD app.py /bin/

EXPOSE 3333

ENTRYPOINT ["/bin/app.py"]
CMD []
