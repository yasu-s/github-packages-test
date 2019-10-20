FROM node:12

WORKDIR /usr/src/app

COPY . .

# パッケージインストール
RUN npm install --production

EXPOSE 3000
CMD ["npm", "run", "start"]
