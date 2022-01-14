# syntax=docker/dockerfile:1
FROM node:16-bullseye
RUN mkdir /app
WORKDIR /app
RUN npm install express \
    && npm install react \
    && npm install create-react-app
EXPOSE 3000/tcp
CMD ["/bin/sh"]
