FROM alpine:3.9

RUN apk add --no-cache curl

RUN ["/bin/ash", "-c", "while [ true ] ; do curl 192.168.1.121:8080/eicar.com; sleep 10; done" ]
