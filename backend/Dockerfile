FROM python:3.13-slim

WORKDIR /app

COPY py_deps.txt py_deps.txt

RUN pip install -r py_deps.txt

COPY main.py .

EXPOSE 8080

CMD ["python", "main.py"]