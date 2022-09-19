FROM node:16
# Create app directory
WORKDIR /usr/src/app

# Bundle app source
COPY . .

# Install app dependencies
RUN npm ci 

EXPOSE 8080
CMD [ "npm", "run", "prod" ]