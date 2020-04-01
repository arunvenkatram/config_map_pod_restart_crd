FROM python:latest
RUN pip install requests json logging sys
WORKDIR /app
COPY controller.py /app/
ENTRYPOINT [ "python", "/app/controller.py" ]