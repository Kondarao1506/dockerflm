FROM node:22.23-alpine3.24
WORKDIR /myapp
COPY package*.json .
RUN npm ci --production
COPY --chown=node:node . .
USER node
CMD ["node" , "app.js"]
