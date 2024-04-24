FROM node:17.7.2
RUN mkdir react-app
WORKDIR /app/react-app
COPY package*.json ./
RUN yarn install
ENTRYPOINT [ "npm", "start" ]