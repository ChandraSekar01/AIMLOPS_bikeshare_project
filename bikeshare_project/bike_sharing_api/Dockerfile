FROM python:3.12.1-slim
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8001
ENV FLASK_APP=bikeshare_model_api
CMD ["python", "app/main.py"]