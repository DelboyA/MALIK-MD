FROM quay.io/naveeddogar/kingmd
RUN git clone https://github.com/arkhan998/MALIK-MD /root/arkhan998
WORKDIR /root/arkhan998/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
