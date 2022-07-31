FROM node:16-alpine

EXPOSE 19000
EXPOSE 19001
EXPOSE 19002
EXPOSE 19006

WORKDIR /usr/app

COPY ./ ./
RUN npm install

RUN npm install --global expo-cli

# Set up a default command
CMD [ "npm", "web" ]