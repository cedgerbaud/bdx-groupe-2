FROM python:3-slim-buster

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .
RUN chmod +x entry_point.sh
CMD [ "./entry_point.sh" ]