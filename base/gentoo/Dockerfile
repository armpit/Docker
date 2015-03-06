FROM scratch

MAINTAINER armpit armpit@rumpigs.net

ADD . /

RUN ["/bin/busybox", "sh", "build.sh"]

ONBUILD RUN env-update
