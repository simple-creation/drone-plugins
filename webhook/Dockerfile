FROM alpine
ADD script.sh /bin/
RUN chmod +x /bin/script.sh
#RUN apk -Uuv add curl ca-certificates
RUN apk update && apk add curl openssh-client busybox-extras vim
ENTRYPOINT /bin/script.sh