FROM node:14

WORKDIR /usr/src/app

COPY example-frontend .

RUN npm install

ENV REACT_APP_BACKEND_URL=http://localhost:8081

RUN npm run build

RUN npm install -g serve

CMD ["serve","-s","-l","5000","build"]

EXPOSE 5000