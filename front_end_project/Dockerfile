FROM node:latest
WORKDIR /app
COPY package*.json ./
COPY .npmrc .npmrc
RUN npm install
RUN npm install dotenv
RUN npm install react-scripts
RUN npm install react-router-dom@5.2.0
RUN npm install axios
COPY . .
EXPOSE 3000
CMD ["npm","start"]
