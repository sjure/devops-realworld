FROM node:14-alpine
WORKDIR /usr/src/app
# Step 1/2: install react

COPY package*.json /usr/src/app/
RUN npm install
COPY . /usr/src/app/

EXPOSE 3000
# Step 2/2: Run all
CMD ["npm", "start" ]
