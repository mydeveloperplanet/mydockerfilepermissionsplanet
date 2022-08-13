FROM alpine:3.16.2

RUN addgroup --g 1024 groupcontainer
RUN adduser -u 1024 -G groupcontainer -h /home/containeruser -D containeruser

USER containeruser

RUN mkdir /home/containeruser/testdir
