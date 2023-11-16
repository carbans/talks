FROM alpine
RUN addgroup -S myuser && adduser -S myuser -G myuser
RUN apk add cowsay --repository=http://dl-cdn.alpinelinux.org/alpine/edge/testing/
USER myuser
