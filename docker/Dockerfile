FROM node:latest

# ------- 環境変数設定 -------------
# ルートディレクトリの設定
ENV rootdir /home/web

WORKDIR ${rootdir}
COPY ./container/package*.json /home/web
RUN npm install
