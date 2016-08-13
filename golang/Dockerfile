FROM worzeel/tmux:golang

COPY .vim /root/.vim
COPY .vimrc /root/.vimrc

RUN apk update \
    && apk upgrade \
    && apk add vim git \
    && git clone https://github.com/fatih/vim-go.git ~/.vim/bundle/vim-go \
    && rm -rf /var/cache/apk/*
