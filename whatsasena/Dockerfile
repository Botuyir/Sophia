FROM fusuf/whatsasena:latest

RUN githttps://github.com/Hisham-Muhammed/Sophia clone /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
