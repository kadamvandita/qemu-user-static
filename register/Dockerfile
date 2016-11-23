FROM s390x/busybox
ENV QEMU_BIN_DIR=/usr/bin
ADD ./register.sh /register
ENTRYPOINT ["/register"]
