# 拡張機能入りdokcer image
FROM klakegg/hugo:0.111.3-ext-debian
RUN apt update && apt -y install nodejs git
RUN unlink /etc/localtime && \
    ln -s /usr/share/zoneinfo/Asia/Tokyo /etc/localtime
RUN git config --global user.name "halflite" && \
    git config --global user.email shingo@halflite.net