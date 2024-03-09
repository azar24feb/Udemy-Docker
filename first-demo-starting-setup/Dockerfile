FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node", "app.mjs" ]
# writing image sha256:d25af4669beae75c5b9f8454caa69a2ebae8f7cb16c6b5eedf8e21c39ec8252f  