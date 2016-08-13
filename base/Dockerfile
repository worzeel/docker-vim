FROM worzeel/tmux

RUN apk update \
    && apk upgrade \
    && apk add vim \
    && rm -rf /var/cache/apk/*

COPY .vim /root/.vim
COPY .vimrc /root/.vimrc
