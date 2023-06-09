# base image Node
FROM node:16

# Create app directory
WORKDIR /app

# Who is the owner
LABEL MAINTAINER=Reis-Pinnock

# Copy app to work dir
COPY app/ .

# use port 3000
EXPOSE 3000

# install npm
RUN npm install

# excecute commands
CMD ["npm", "start", "daemon off;"]
