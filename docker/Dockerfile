FROM python:3.8.10
RUN pip install --no-cache-dir sqlite_web
EXPOSE 8080
VOLUME /data
WORKDIR /data
CMD sqlite_web -H 0.0.0.0 -x $SQLITE_DATABASE
