Dell Store 2
============

http://linux.dell.com/dvdstore/

PostgreSQL port of the Dell Store 2 database

INSTALL
-------

a) Download and unpack the file: dellstore2-normal-1.0.rar

b) At a terminal (command prompt) type:

createdb -U username dellstore2

psql -U username -f dellstore2-normal-1.0.sql dellstore2
