FROM lang/chicken

RUN apk-install libgit2-dev@testing
RUN chicken-install git

RUN adduser -D -s /bin/sh sandbox
WORKDIR /home/sandbox
USER sandbox
