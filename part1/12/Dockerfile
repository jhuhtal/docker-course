FROM node

EXPOSE 5000

RUN node -v && npm -v
RUN npm install -g serve

CMD serve -s -l 5000 build