FROM node:18-alpine
 
WORKDIR /usr/src/app
 
COPY package.json /usr/src/app
COPY package-lock.json /usr/src/app
 
RUN npm install
 
COPY . .
 
EXPOSE 3000
 
CMD [ "npm", "run", "dev" ]