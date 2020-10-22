FROM python:alpine
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["worker.py"]

ENTRYPOINT ["python"]
