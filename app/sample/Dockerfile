FROM       ubuntu
RUN        apt update
WORKDIR    /app/sample
COPY       . ./app
RUN        apt install npm -y
RUN        npm install
RUN        npm start


