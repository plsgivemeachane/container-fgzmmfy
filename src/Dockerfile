# A simple node.js image
FROM node:latest
WORKDIR /usr/src
COPY . .
RUN npm install
RUN npm install -g pm2
RUN pm2 link uhyz7tcoimeb81b yrzs0totz1wqh2d

EXPOSE 5000
CMD ["pm2-runtime", "start", "index.js"]