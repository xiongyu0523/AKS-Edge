FROM node:18.12.1-alpine3.15

ENV REDIS_HOST=localhost
ENV REDIS_PORT=6379
ENV VOTESERVER_PORT=50001
ENV CANDIDATE_1_NAME=Cat
ENV CANDIDATE_2_NAME=Dog

WORKDIR /app

COPY [ "./", "/app"]

RUN npm install

CMD [ "node", "app.js" ]