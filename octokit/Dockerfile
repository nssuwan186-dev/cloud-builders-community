FROM node:25.6.0-bookworm as builder

ADD . .

RUN npm ci
RUN npx tsc

ENTRYPOINT ["node", "/build/index.js"]
