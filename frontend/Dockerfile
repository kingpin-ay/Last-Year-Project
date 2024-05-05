FROM node:21.5.0-alpine

WORKDIR /app
COPY . .
RUN npm i

RUN npm run build

CMD [ "npm", "run", "start" ,"--" ,"-H" ,"192.168.0.100" ]