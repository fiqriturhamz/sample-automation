# USE An existing docker image as a base
FROM alpine

# Download and install depedancy
RUN apk add --update redis
RUN mkdir -p /home/eversafe/storage
RUN mkdir -p /home/eversafe/log
# Tell the image what to do and what

CMD [ "redis-server" ]
