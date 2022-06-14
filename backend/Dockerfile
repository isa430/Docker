FROM node:10.15.3-alpine
WORKDIR /app
COPY . .
RUN npm install express --save
CMD ["node", "index.js"]
EXPOSE 5000