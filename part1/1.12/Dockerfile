FROM node:16
WORKDIR /usr/app/src
COPY ./example-frontend .
RUN npm install
RUN npm install -g serve
EXPOSE 5000
RUN npm run build
CMD ["serve", "-s", "-l", "5000", "build"]