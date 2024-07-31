FROM python:3.10-alpine
WORKDIR /app
ENV ENV PROD 
ENV AUTHOR RAVSHAN
COPY reqs.txt .
RUN pip install -r reqs.txt
COPY . .
CMD [ "python", "app.py" ]
