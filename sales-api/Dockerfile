FROM node:14
WORKDIR .
COPY package*.json ./
RUN yarn
COPY . .
EXPOSE 9090
CMD ["node", "app.js"]