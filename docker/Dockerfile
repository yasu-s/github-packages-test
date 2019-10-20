FROM node:12

WORKDIR /usr/src/app

COPY . .

# パッケージインストール
RUN npm install

EXPOSE 3000
CMD ["npm", "run", "start"]
