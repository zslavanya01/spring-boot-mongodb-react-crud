FROM       node:alpine
WORKDIR    /app
ENV        PATH /app *:$PATH
COPY       package.json ./
COPY       package-lock.json ./
RUN        npm insatll
COPY       . ./
CMD        [ "npm" , "start" ]