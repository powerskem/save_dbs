################
save_dbs.sh

K P Chase
################

Call the script:
./save_dbs.sh [OPTIONS] database1 database2 ...

e.g.
./save_dbs.sh --remote location -u user -p password db1 db2 db3

The program will:
- use pg_dump to back up the database to a .sql file (location is currently hard-coded)
