# lizmap_sqlite2postgresql
It is a simple script for [pgloader](https://github.com/dimitri/pgloader) which convert the sqlite lizmap DB to a postgresql DB. 

To run it (on ubuntu): 

 1) clone pgloader
 
 2) checkout v.3.6.1 or later
 
 3) compile it
 
> make pgloader
 
 
 4) enter in the bin folder
 
> cd bulid/bin/ 

5) use the postgres user

> sudo su postgres
  
with the sudo password

then 

> ./pgloader path_to_script/lizmap_jauth_db.load



Any help to  refine the instructions for different O.S. is appreciated!
