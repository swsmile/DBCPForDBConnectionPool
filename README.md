# DBCPForDBConnectionPool
Use DBCP to realise database connection pool.

Once runnning this program, the connection between this client and mysql databse will be kept open, until this program is terminated.

We can use `netstat -an | grep 3306` to see the open tcp between the client and mysql.
