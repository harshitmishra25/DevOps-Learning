FROM python:3.10-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
ENV ENV_VALUE="Running in Docker"
EXPOSE 3000
CMD [ "python" , "main.py" ]
