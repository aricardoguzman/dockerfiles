FROM node:10.0.0

RUN npm install -g nodemon

WORKDIR /var/www/app

RUN cd /var/www/app 
RUN git clone https://github.com/kirvi456/analisisRepo2.git . 
RUN npm install

EXPOSE 8081

CMD nodemon app.js
