FROM node:16
WORKDIR /usr/app/src
COPY ./example-frontend .
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]