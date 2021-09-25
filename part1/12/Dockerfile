FROM node

EXPOSE 5000

ENV NODE_ENV=production
ENV REACT_APP_BACKEND_URL=localhost:8080

WORKDIR /usr/src/app

COPY . .

RUN npm install
RUN npm run build
RUN node -v && npm -v
RUN npm install -g serve

CMD serve -s -l 5000 build