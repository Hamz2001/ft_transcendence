FROM python:3.11

# RUN apt-get update && apt-get install -y zsh

# RUN apt-get install -y curl && \
#     sh -c "$(curl  -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

RUN apt-get update && \
    apt-get install -y libnss3-tools dos2unix
COPY requirements.txt .
RUN pip3 install -r requirements.txt
COPY ./second_game/ /second_game
# COPY chatProject/env /

COPY script.sh .
ENV PYTHONUNBUFFERED=1

RUN chmod +x script.sh
RUN dos2unix script.sh
# WORKDIR /chatProject
ENTRYPOINT [ "./script.sh" ]

