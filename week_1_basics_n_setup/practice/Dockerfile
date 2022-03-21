FROM python:3.9

RUN pip install pandas

WORKDIR /app

COPY pipeline.py pipe.py

ENTRYPOINT ["python", "pipe.py"] 
# this is the entrypoint for the container to run python and then pipe.py file