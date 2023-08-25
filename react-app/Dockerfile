FROM node:18-alpine

# Working director
WORKDIR /react-app

# Copy some pubic folder
COPY . /react-app

# Install packages
RUN npm install

# RUN npm run start
# # Run app
CMD [ "npm", "start" ]