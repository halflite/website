FROM klakegg/hugo:0.80.0-ext-ubuntu
RUN apk update && apk --no-cache add git tzdata && \
  cp /usr/share/zoneinfo/Asia/Tokyo /etc/localtime && \
  apk del tzdata && \
  git clone https://github.com/vickylai/hugo-theme-sam.git themes/sam
