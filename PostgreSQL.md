# PostgreSQL

### Connection Failure

    Error:

    psql: could not connect to server: No such file or directory
    Is the server running locally and accepting
    connections on Unix domain socket "/tmp/.s.PGSQL.5432"?

    Solution:

    cd ~
    rm /usr/local/var/postgres/postmaster.pid
