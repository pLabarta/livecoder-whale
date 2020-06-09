FROM node

RUN apt update -y

RUN apt install git -y

WORKDIR /hydra
RUN git clone https://github.com/ojack/hydra
WORKDIR /hydra/hydra
RUN npm install -d

EXPOSE 8080

CMD npm run start