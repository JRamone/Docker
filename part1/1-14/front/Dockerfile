FROM node:14-alpine

COPY ./example-frontend .

EXPOSE 5000

ENV REACT_APP_BACKEND_URL=http://localhost:5000
RUN npm install
RUN npm run build
RUN npm install -g serve
CMD ["serve","-s","-l","5000","build"]

