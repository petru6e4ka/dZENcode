FROM node:18

RUN mkdir -p /dzen
WORKDIR /dzen

COPY /package.json /dzen
RUN npm i

COPY . /dzen

EXPOSE 3000
CMD ["./start.sh"]
