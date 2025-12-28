FROM node:current-alpine
COPY . /app
WORKDIR /app
RUN ls
RUN npm install

ENTRYPOINT ["npm", "start"]
