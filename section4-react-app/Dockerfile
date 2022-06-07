FROM node:14.16.1-alpine3.13
WORKDIR /app
copy . .
RUN npm install 
EXPOSE 3000
ENV NAME=hothaifa
ENTRYPOINT [ "npm" , "start" ]