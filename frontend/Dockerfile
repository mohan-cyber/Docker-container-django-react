# Name the node stage "builder"
FROM node:14 AS builder
# Set working directory
WORKDIR /frontend
# Copy all files from current directory to working dir in image
COPY . .
# install node modules and build assets
RUN yarn install 


EXPOSE 3000

CMD ["yarn", "start"]