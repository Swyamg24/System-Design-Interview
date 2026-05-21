## Single server setup ##
everything is running on single server.
user gives website name and gets ip and give ip to server and gets web page 

## Database ##
with the expansion of users , we need database and multiple servers one for web traffic and another for data traffic.
we can scale both servers independently using different servers for different purposes.

## Which databases to use? ##
Two type of database - relational and non relational
relational - In table format , for structured data , Secure , used in banking and other
non relational - for unstructured data , fast , easy to create 

## Vertical scaling vs horizontal scaling ##
vertical scaling is increasing the cpu power and memory of single server
horizontal scaling is increasing number of servers
Horizontal scaling is more desirable for large scale applications due to the limitations of
vertical scaling.

## Load balancer ##
solves the problem of failover or no backup on server side , prevents website from getting offline
acts between client and the server .
manages that traffic is equally distributed between servers.
load balancer can be hardware , software or cloud based .

## Database replication ##
replicate data between master db and slave db
similar as load balancing in servers but for the db 
master db is for all read , write and other modification commands 
slave db is for read operation only

## Cache ##
Temporary storage for keeping frequently fetched data or expensive data.
improves the performance of application by avoiding repeated calling of db.


