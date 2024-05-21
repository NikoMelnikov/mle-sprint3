FROM python:3.11-slim
COPY . ./cow_dir
WORKDIR cow_dir
RUN ["pip3", "install", "python-cowsay==1.1.0"]
CMD ["python3", "./main.py"]