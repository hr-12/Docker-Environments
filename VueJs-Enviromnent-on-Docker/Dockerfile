FROM node:14.16.1
WORKDIR /app
ADD package.json .
RUN npm install
ADD . .
EXPOSE 8080
CMD ["npm", "run", "serve"]