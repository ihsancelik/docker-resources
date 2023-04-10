FROM node:14-slim
WORKDIR /opt/node-app
COPY . .
RUN npm install
ENV port=3001
CMD ["node", "app.js"]