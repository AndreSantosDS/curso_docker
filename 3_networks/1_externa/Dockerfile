FROM python:3

WORKDIR /app

COPY . .

RUN pip install Flask
RUN pip install requests

EXPOSE 5000

CMD ["python", "app.py"]