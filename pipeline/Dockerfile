# base image
FROM python:3.13.11-slim

# install libraries
RUN pip install pandas pyarrow

# working folder inside the container
WORKDIR /app

# copy the script into the container
COPY pipeline.py pipeline.py

# command that runs when the container starts
ENTRYPOINT ["python", "pipeline.py"]