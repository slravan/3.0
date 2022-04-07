FROM fusuf/whatsasena:latest

RUN git clone https://github.com/slravan/3.0 /root/3.0
WORKDIR /root/3.0/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
