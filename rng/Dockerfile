FROM python:alpine
RUN pip install Flask
COPY rng.py /

ENTRYPOINT ["python"]
CMD ["rng.py"]
EXPOSE 8080
