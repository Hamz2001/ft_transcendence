FROM python:3.11

RUN apt-get update && \
    apt-get install -y libnss3-tools dos2unix
COPY requirements.txt .
RUN python3.11 -m pip install -r requirements.txt
COPY track/ /track/

COPY script.sh .
ENV PYTHONUNBUFFERED=1

RUN chmod +x script.sh
RUN dos2unix script.sh
CMD [ "./script.sh" ]