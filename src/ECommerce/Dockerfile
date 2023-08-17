FROM python:3.8-slim
WORKDIR /server
COPY dependencies.txt .
RUN pip install -r dependencies.txt
COPY app/ .
CMD ["python", "n11.py"]