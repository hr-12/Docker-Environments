FROM node:14.16.1
WORKDIR /app
ADD package.json .
ADD . .
RUN npm install
EXPOSE 3000
CMD ["npm", "run", "dev"]