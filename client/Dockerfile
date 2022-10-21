FROM node:16

WORKDIR /lrpp/client
COPY package.json package-lock.json ./
RUN npm install
COPY ./ ./
ENV HOST=0.0.0.0
CMD ["npm", "start"]
