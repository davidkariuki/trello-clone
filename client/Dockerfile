FROM node:alpine

WORKDIR /app

COPY package*.json /app/
RUN npm install --no-optional
COPY . .

EXPOSE 4000

ENTRYPOINT ["npm", "start"]
