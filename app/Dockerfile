FROM node:12-alpine
WORKDIR /app
RUN sh -c "yarn install && yarn run dev"
COPY . .
CMD ["node", "/app/src/index.js"]

