Cancel job
----------
    /usr/bin/enq  -P 'printqueue' -x '62'


Stop queue
----------
    /usr/bin/enq -D -P 'pqueue:hp@HOST'

`hp@HOST` case matters and is what was entered when making the jetdirect printer


Start queue
-----------
    /usr/bin/enq -U -P 'pqueue:hp@HOST'

`hp@HOST` case matters and is what was entered when making the jetdirect printer


Show jobs
---------
    /usr/sbin/piomisc_base get_job_status -P 'printqueue'


Queue Status
------------
    /usr/bin/enq -A -e
