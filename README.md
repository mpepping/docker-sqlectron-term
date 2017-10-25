# sqlectron-term

[sqlectron-term](https://sqlectron.github.io) is a node/ncurses based database-client for the cli. Currently sqlectron supports MySQL and Postgres.


## Usage

Quick && dirty

    docker run -ti mpepping/sqlectron-term

Persisting state locally:

    docker run -ti -v \
    $PWD/Sqlectron:/home/sqlectron/.config/Sqlectron \
    mpepping/sqlectron-term

Change the default `vim` editor to `nano`:

    docker run -ti -v --env EDITOR=nano \
    mpepping/sqlectron-term
