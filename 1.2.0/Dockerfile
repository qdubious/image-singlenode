FROM springxd/base:1.2.0
MAINTAINER Eric Bottard

RUN mkdir -p /tmp/xd/output
RUN mkdir -p /tmp/xd/input
RUN chown springxd /tmp/xd/output
RUN chown springxd /tmp/xd/input

CMD ["xd/bin/xd-singlenode"]
EXPOSE 9393
