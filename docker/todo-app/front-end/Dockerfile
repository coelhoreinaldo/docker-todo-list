FROM node:16.19-alpine

WORKDIR /app/front-end

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]

EXPOSE 3000