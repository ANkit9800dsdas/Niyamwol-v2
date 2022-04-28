FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Blackmaac/Niyamwol-v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/Blackmaac/media

CMD ["node", "bot.js"]
