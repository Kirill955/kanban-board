FROM node:20-slim

WORKDIR /frontend

COPY package.json package-lock.json ./

RUN npm install

COPY . /frontend

# Убедиться что vite доступен
RUN ls -la node_modules/.bin/ | grep vite

CMD ["npm", "run", "dev"]
