FROM --platform=linux/amd64 node:lts-alpine
WORKDIR ./app
COPY . .
RUN yarn install --production
CMD ["node", "index.js"]
EXPOSE 3000