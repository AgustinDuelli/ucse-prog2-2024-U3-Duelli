## Dockerfile for app1 exposed on port 4000
FROM node:22-alpine
WORKDIR /app2
COPY package*.json /app2
RUN npm install
COPY . /app2
EXPOSE 4001
CMD ["npm", "start"]
