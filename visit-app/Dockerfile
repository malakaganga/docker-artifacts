#Create base image using existing image
FROM node:alpine
#Download and install depedency
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./
#Add start up command
CMD ["npm", "start"]