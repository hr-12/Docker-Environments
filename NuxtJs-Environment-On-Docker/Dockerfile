FROM node:14.16.1
WORKDIR /app
CMD [ "apk", "update", "&&", "apk", "upgrade"]
CMD [ "apk add git" ]
ADD . .
RUN npm install
EXPOSE 5000
ENV NUXT_HOST=0.0.0.0
ENV NUXT_PORT=5000
CMD ["npm", "run", "dev"]