FROM python:3.11-slim

WORKDIR /app

RUN --mount=type=bind,source=requirements.txt,target=requirements.txt \
    python -m pip install --no-cache-dir -r requirements.txt

COPY . .

CMD ["python", "app.py"]
