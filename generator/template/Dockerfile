FROM node:10.10.0

WORKDIR /usr/src/app

COPY package.json ./
COPY yarn.lock ./
RUN yarn

COPY . .

CMD ["yarn", "serve"]
