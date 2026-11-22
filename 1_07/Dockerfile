FROM ubuntu:24.04

RUN apt-get update && apt-get install -y curl

WORKDIR /app

COPY script.sh .

RUN chmod +x script.sh

CMD ["./script.sh"]
