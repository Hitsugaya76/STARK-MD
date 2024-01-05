FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Hitsugaya76/Stark-mdt /root/SuhailTech_BOt
WORKDIR /root/SuhailTech_BOt/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
 
