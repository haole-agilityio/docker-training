FROM node:18-alpine

# Working director
WORKDIR /react-app

# Copy some pubic folder
COPY . /react-app

# Install packages
RUN npm install

# RUN npm run start
EXPOSE 5173

# Run app
CMD [ "npm", "start" ]