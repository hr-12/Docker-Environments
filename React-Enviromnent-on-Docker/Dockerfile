FROM node:14.16.1
WORKDIR /app
ADD package.json .
RUN npm install
ADD . .
EXPOSE 3000
CMD ["npm", "start"]