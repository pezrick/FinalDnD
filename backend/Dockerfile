FROM python:3.7.4
WORKDIR /backend
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5003
ENTRYPOINT [ "python", "app.py" ]