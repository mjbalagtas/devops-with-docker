FROM ubuntu:20.04
RUN apt-get update && apt-get install curl -y
COPY script.txt .
RUN chmod +x script.txt
CMD ./script.txt
