FROM alpine:3.16.2

RUN addgroup --g 1000 groupcontainer
RUN adduser -u 1000 -G groupcontainer -h /home/containeruser -D containeruser

USER containeruser

COPY test.txt /home/containeruser/test.txt
