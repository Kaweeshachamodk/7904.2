FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Kaweeshachamodk/7904.2.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/AiDarkEzio/medias.git
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
