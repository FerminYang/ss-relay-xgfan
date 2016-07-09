ss-relay based on haproxy
==========

build
-----

    docker build .

run
---

    docker run -d -v /confdir:/usr/local/etc/haproxy/ dochang/cow:latest
