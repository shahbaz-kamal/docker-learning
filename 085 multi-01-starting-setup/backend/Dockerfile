FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000

ENV MONGODB_USERNAME=tamim

ENV MONGODB_PASSWORD=12345


CMD ["npm","start"] 