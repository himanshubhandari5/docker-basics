ARG NODE_VER=20
FROM node:${NODE_VER}

MAINTAINER Himanshu Bhandari

WORKDIR /app
COPY . .

ENV PORT=3000
RUN npm install
EXPOSE $PORT

ENTRYPOINT ["node"]
CMD ["app.js"]