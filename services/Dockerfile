FROM strapi/base

ARG NODE_ENV

WORKDIR /opt/app

COPY ./package.json ./

RUN yarn install

COPY . .

ENV NODE_ENV ${NODE_ENV}

RUN yarn build

EXPOSE 1337

CMD ["yarn", "start"]
