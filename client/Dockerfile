FROM node:latest
WORKDIR /app
COPY . .
RUN npm i
RUN npm run build
RUN npm i -g serve
COPY ./dist .
CMD ["serve", "."]

