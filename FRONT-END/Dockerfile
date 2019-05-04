FROM node:10.0.0

RUN npm install -g nodemon

WORKDIR /var/www/app

RUN cd /var/www/app && git clone https://github.com/kirvi456/analisisRepo2.git . && npm install

EXPOSE 8081

CMD nodemon app.js
