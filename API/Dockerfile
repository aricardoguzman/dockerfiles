FROM node:10.0.0

RUN npm install -g nodemon

WORKDIR /var/www/api

RUN cd /var/www/api && git clone https://github.com/kirvi456/analisisRepo1.git . && npm install

EXPOSE 5000

CMD npm start
