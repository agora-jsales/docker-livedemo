FROM node

WORKDIR /app

COPY ./package.json .

RUN npm install

COPY . .

# Its used "npm start" because in package.json script we use the start command to execute the react-scripts start
CMD [ "npm", "start" ]