FROM fusuf/whatsasena:latest

RUN git clone https://github.com/SHALU-SER/Abu_ser /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/SHALU-SER/media

CMD ["node", "bot.js"]
