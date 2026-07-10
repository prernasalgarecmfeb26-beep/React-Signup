FROM node:20
WORKDIR /React-Signup

COPY package*.json ./

RUN npm install
COPY . .

CMD ["npm", "run", "dev"]