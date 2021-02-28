# CS4604 Labs
These labs will use relational database management systems (RDBMS), e.g. [PostgreSQL](https://www.postgresql.org/), [SQLite](https://www.sqlite.org/index.html), [MySQL](https://www.mysql.com/), [MariaDB](https://mariadb.org/) and non-relational databases e.g. MongoDB.

`PostgreSQL` is a free and open-source relational database management system emphasizing extensibility and SQL compliance. It was originally named POSTGRES, referring to its origins as a successor to the Ingres database developed at the University of California, Berkeley.

`SQLite` is an in-process library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. The code for SQLite is in the public domain and is thus free for use for any purpose, commercial or private. 

MySQL is an open-source relational database management system. Its name is a combination of "My", the name of co-founder Michael Widenius's daughter, and "SQL", the abbreviation for Structured Query Language.

MariaDB is a community-developed, commercially supported fork of the MySQL relational database management system, intended to remain free and open-source software under the GNU General Public License.

## Labs

Each individual folder has instructions for that particular lab. For example, see [0.test-setup](0.test-setup)
* [0.test-setup](0.test-setup/)
* [1.ddl_dml](1.ddl_dml/)
* [2.select](2.select/)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VTCourses/CS4604_Labs/blob/master/2.select/Lab_2.ipynb)
* [3.more_queries](3.more_queries/)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VTCourses/CS4604_Labs/blob/master/3.more_queries/Lab_3.ipynb)
* [4.joins](4.joins/)    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VTCourses/CS4604_Labs/blob/master/4.joins/Lab_4.ipynb)
* [5.indexing](5.indexing/)


## SQLite
* Installation: https://www.sqlite.org/download.html
* SQLite is also available in ap1.cs.vt.edu and rlogin.cs.vt.edu
* [SQLite In 5 Minutes Or Less](https://www.sqlite.org/quickstart.html)
* [Command Line Shell For SQLite](https://sqlite.org/cli.html#:~:text=Terminate%20the%20sqlite3%20program%20by,a%20long%2Drunning%20SQL%20statement.)
* [SQLite cheat sheet](docs/sql-sqlite-commands-cheat-sheet.pdf)

## PostgreSQL
* Installation: https://www.postgresql.org/download/
* [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)
* [Psql Guide](http://postgresguide.com/utilities/psql.html)
* [PostgreSQL Cheat Sheet](docs/PostgreSQL-Cheat-Sheet.pdf)

## Jupter Notebooks
* Python 3 installation: [Python Tutorial](https://github.com/VTCourses/Python_tutorial)
* [Anaconda Individual Edition](https://www.anaconda.com/products/individual): It is optional but strongly recommended. It would make your life easier.
* Dependencies installation: See [requirements.txt](requirements.txt)
	```
	pip3 install -r requirements.txt (Python 3)
	```

## Database client
* [pgAdmin](https://www.pgadmin.org/)
	* [How to connect to a database](pgadmin.md)
* [How to install psql on Mac, Ubuntu, Debian, Windows](https://blog.timescale.com/tutorials/how-to-install-psql-on-mac-ubuntu-debian-windows/)

## Online Database for practice
* [Pdbmbook Playgrounds](https://www.pdbmbook.com/playground/)
* [MySQL online](https://extendsclass.com/mysql-online.html#)
* [PostgreSQL online](https://extendsclass.com/postgresql-online.html)
* [SQLite browser online](https://extendsclass.com/sqlite-browser.html)

## Attribution

The content for some labs has been adopted form the previous CS4604 labs created by Richard Quintin: rquintin@vt.edu

This Spring 2021 class adds Jupter Notebooks for some labs and new labs.