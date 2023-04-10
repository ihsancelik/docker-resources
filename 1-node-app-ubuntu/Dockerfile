FROM ubuntu:18.04
RUN apt update
RUN apt install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install nodejs -y
WORKDIR /opt/node-app/
COPY . .
ENV channel="İhsan Ç."
CMD ["node", "index.js"]