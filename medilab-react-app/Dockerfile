FROM node:14.19.3
RUN mkdir /opt/medilab-react-app
WORKDIR /opt/medilab-react-app
COPY . $WORKDIR
RUN npm install
CMD [ "npm","start" ]