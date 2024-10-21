FROM python3:alpine3.19

WORKDIR /app

COPY requirements.txt

RUN python3 -V
RUN pip3 install --no-cache-dir -r requirements.txt

COPY . .

CMD ["python3", "/app/main.py"]