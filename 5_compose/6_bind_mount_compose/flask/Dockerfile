FROM python:3

WORKDIR /app

COPY . .

RUN pip install Flask
RUN pip install requests
RUN pip install flask_mysqldb

EXPOSE 5000

CMD ["python", "app.py"]