FROM node:lts-alpine

WORKDIR /astro-app

ENV PATH /astro-app/node_modules/.bin:$PATH

COPY *.json ./

RUN cd /astro-app && npm install 

COPY . /astro-app

CMD ["npm","run","start","--","--host"]
