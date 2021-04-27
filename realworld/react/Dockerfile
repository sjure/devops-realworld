FROM node:14-alpine
WORKDIR /usr/src/app
# Step 1/2: install react

COPY package*.json /usr/src/app/
RUN npm install
COPY . /usr/src/app/
# npm build
# serve -s build -l 3000
EXPOSE 3000

