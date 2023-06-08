FROM   registry.access.redhat.com/ubi8/ubi:8.0
ADD test.sh .
RUN chgrp -R 0 test.sh && \
    chmod -R g=u test.sh
ENTRYPOINT ["/test.sh"]
