FROM       node:10-alpine
RUN        apt update -y
WORKDIR    /app/sample
COPY       package-lock.json /app
COPY       package.json /app
RUN        apt install npm -y
RUN        npm install
CMD        ["npm","start"]

