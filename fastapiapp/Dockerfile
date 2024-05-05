FROM python:3.10

WORKDIR /code

COPY requirements.txt /code/

RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

COPY app /code/

CMD ["fastapi", "run", "app/main.py", "--port", "8000"]
