FROM node:16

WORKDIR /usr/src/app

COPY . .
RUN npm ci 

ENV SET DEBUG=playground:*
  
USER node
CMD ["npm", "run", "dev"]