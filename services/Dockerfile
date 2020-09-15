FROM strapi/base

WORKDIR /opt/app

COPY ./package.json ./
COPY ./package-lock.json ./

RUN yarn install

COPY . .

ENV NODE_ENV development

RUN yarn build

EXPOSE 1337

CMD ["yarn", "start"]
