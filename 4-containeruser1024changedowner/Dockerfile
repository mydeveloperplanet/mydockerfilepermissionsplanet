FROM alpine:3.16.2

RUN addgroup --g 1024 groupcontainer
RUN adduser -u 1024 -G groupcontainer -h /home/containeruser -D containeruser

USER containeruser

COPY --chown=containeruser:groupcontainer test.txt /home/containeruser/test.txt
