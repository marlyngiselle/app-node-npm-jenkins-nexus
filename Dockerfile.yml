FROM node:16
WORKDIR /app
COPY miApp/package*.json ./
RUN npm install
COPY miApp/* ./
EXPOSE 3000
CMD [ "node" , "index.js"]