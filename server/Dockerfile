FROM node:18-alpine as development

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "run", "start:dev"]



# FROM node:latest as development

# WORKDIR /usr/src/app

# COPY . .

# RUN rm -rf package-lock.json && npm install && npm run build

# EXPOSE 5000

# CMD ["npm", "start"]
