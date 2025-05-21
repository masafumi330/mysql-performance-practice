# mysql-performance-practice

## Setup
1. Download sample database 'world database' Zip from https://dev.mysql.com/doc/index-other.html and Unpack.
2. move unpacked world-db/world.sql to project root dir
3. `$ docker compose up -d`
4. `$ docker exec -it db /bin/bash`
5. `bash-4.4# cd /usr/local/src/`
6. `bash-4.4# mysql -uroot -h 127.0.0.1 -P 3306 -pmy-secret-pw`
7. `mysql> source world.sql`
