FROM quay.io/lyfe00011/md:beta

RUN git clone https://github.com/kaweeshachamo/7904.2.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/kaweeshachamo/medias.git
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
