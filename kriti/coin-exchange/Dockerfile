FROM node:16-alpine3.11
WORKDIR /home/coin/
COPY app.js ./app.js
COPY index.html ./index.html
COPY package.json ./package.json
RUN npm i

ENV FLAG "KR25{b_th3_BEST!}"
ENV ADMIN_TOKEN "d6ccfd3a4cc18807825030209caa91a71bc074bd0bef2a516f7374a3576c0595"

CMD ["node", "app.js"]
