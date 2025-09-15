FROM python:3.11-slim
WORKDIR /app
COPY . .
RUN pip install flask redis
EXPOSE 5002
CMD ["python", "count.py"]


