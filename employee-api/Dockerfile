FROM node:22.9.0

WORKDIR "/app/"

ADD package.json /app/

RUN npm install

COPY . "/app/"

CMD ["node", "index.js"]
