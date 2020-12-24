FROM salvadorhm/fastapi:latest
WORKDIR /usr/src/app
COPY fastapi_demo/ ./
EXPOSE 8000
#CMD ["python3", "app.py"]
CMD uvicorn main:app --host 0.0.0.0
