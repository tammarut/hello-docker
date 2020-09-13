FROM node:alpine
LABEL maintainer "Somprasong Damyos"
WORKDIR /nodeapp
COPY app /nodeapp
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]
