ARG ST2_VERSION
FROM stackstorm/st2:${ST2_VERSION}
LABEL com.stackstorm.component="st2resultstracker"

USER st2

CMD ["/opt/stackstorm/st2/bin/st2resultstracker", "--config-file=/etc/st2/st2.conf", "--config-file=/etc/st2/st2.docker.conf", "--config-file=/etc/st2/st2.user.conf"]
