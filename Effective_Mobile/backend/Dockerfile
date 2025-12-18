ROM python:3.12-slim

WORKDIR /app

# создаём непривилегированного пользователя
RUN useradd -m appuser
USER appuser

COPY app.py .

EXPOSE 8080

CMD ["python", "app.py"]