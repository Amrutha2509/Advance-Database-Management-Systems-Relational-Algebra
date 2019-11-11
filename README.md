# Relational-Algebra
Write queries in Relational Algebra, Tuple Relational Calculus and Domain Relational Calculus using DES Datalog
The RDBMS for this project is the http://des.sourceforge.net/, or DES.
The database is Luis Rocha’s Chinook Database,https://github.com/lerocha/chinook-database, modified for use with DES
Once you have downloaded DES, use the following commands to install rlwrap, which will make it easier to interact with the DES console by providing line editing and command history:
$ sudo apt update
$ sudo apt install --yes rlwrap
Then use the following commands to extract and start DES:
$ unzip ~/Downloads/DES6.2Linux64SICStus.zip
$ cd des
$ chmod +x des des_start
$ rlwrap ./des
Loading the Database
Download the database file Chinook_DES.ddb and place it in the same directory where you extracted DES. The database can be loaded with the following command:
DES> /restore_ddb Chinook_DES.ddb

Queries
Write queries in Relational Algebra, Tuple Relational Calculus, and Domain Relational Calculus to determine each of the following:
Albums by the artist “Red Hot Chili Peppers.”
Genres associated with the artist “U2.”
Names of tracks on playlist “Grunge” and their associated artists and albums.
Names and email addresses of customers who bought tracks in playlist “TV Shows.”
Names of the support representatives whose customers bought tracks in “Purchased AAC audio file” format.

