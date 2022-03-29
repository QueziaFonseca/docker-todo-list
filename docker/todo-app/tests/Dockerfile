
FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests
COPY package.json .
COPY package-lock.json .
ADD node_modules.tar.gz .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "test"]
