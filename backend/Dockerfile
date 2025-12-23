FROM python:3.12-slim

WORKDIR /app

RUN useradd -r -u 1001 appuser
USER appuser

COPY app.py .

EXPOSE 8080

CMD ["python", "app.py"]
