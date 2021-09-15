FROM node:alpine

RUN apk add curl vim # 方便调试
EXPOSE 80 3000
WORKDIR /app
COPY app.js .


CMD ["node", "app.js"]
