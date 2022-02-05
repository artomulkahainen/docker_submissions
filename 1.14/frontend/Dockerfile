FROM node:16
WORKDIR /usr/app/src
COPY . .
RUN npm install
RUN npm install -g serve
ENV REACT_APP_BACKEND_URL=http://localhost:8080
EXPOSE 5000
RUN npm run build
CMD ["serve", "-s", "-l", "5000", "build"]