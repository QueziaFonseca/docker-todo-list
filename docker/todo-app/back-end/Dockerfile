FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
COPY package.json .
COPY package-lock.json .
ADD node_modules.tar.gz .
RUN npm install
COPY . .
EXPOSE 3001
CMD ["npm", "start"]
