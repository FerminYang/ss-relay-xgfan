ss-relay based on haproxy
==========

build
-----

    docker build -t my_ss_relay .

run
---

    docker run -d -v /confdir:/usr/local/etc/haproxy/ ferminyang/ss-relay-xgfan:latest
