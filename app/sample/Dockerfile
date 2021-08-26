FROM       node:10-alpine
RUN        apt update
WORKDIR    /app/sample
COPY       package-lock.json /app
COPY       package.json /app
RUN        apt install npm -y
RUN        npm install
RUN        npm start


