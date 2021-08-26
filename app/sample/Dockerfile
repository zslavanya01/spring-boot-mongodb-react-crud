FROM       ubuntu
RUN        apt update
RUN        apt upgrade
WORKDIR    /app/sample
COPY       package-lock.json /app
COPY       package.json /app
RUN        apt install npm -y
RUN        npm install
CMD        ["npm","start"]
