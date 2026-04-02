FROM node:20-alpine
WORKDIR /app
RUN npm install -g @nestjs/cli@10
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["nest", "start", "--watch"]
