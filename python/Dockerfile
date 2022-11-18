FROM python:3.11-slim

RUN pip install numpy

RUN mkdir -p /opt/myapp

COPY my_numpy_dependent_script.py /opt/myapp

WORKDIR /opt/myapp

CMD ["python3","my_numpy_dependent_script.py"]