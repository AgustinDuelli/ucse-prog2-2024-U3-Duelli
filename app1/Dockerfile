## Dockerfile for app1 exposed on port 4000
FROM node:22-alpine
WORKDIR /app1
COPY package*.json /app1
RUN npm install
COPY . /app1
EXPOSE 4000
CMD ["npm", "start"]
