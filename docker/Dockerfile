From node:14-alpine

WORKDIR /usr/src/app

# linux Update, set Timezone, install bash
RUN apk --update add tzdata && \
    cp /usr/share/zoneinfo/Asia/Tokyo /etc/localtime && \
    apk del tzdata && \
    apk add --no-cache bash

# npm Update
RUN npm install -g npm
