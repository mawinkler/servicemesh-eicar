FROM alpine:3.9

RUN apk add --no-cache curl

CMD ["/bin/ash", "-c", "while [ true ] ; do curl eicarserver:80/eicar.com; sleep 10; done" ]
