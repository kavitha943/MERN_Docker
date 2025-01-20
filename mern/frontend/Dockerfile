FROM node:11.0.0

WORKDIR /app
COPY package.json .
RUN npm install
COPY . . 
EXPOSE 5173
CMD ["npm", "run", "dev"]

