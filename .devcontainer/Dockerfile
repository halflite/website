FROM klakegg/hugo:0.111.3-alpine
RUN apk update && apk --no-cache add git tzdata && \
    cp /usr/share/zoneinfo/Asia/Tokyo /etc/localtime && \
    apk del tzdata && \
    git config --global user.name "halflite" && \
    git config --global user.email shingo@halflite.net
