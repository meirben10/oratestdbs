# oratestdbs
Script for checking if all local network databases (Oracle, SQL Server) connections available 

this script is running on one of the machine in your local network.
it run a loop that check the connection (and more...) to all the databases in the network.
Based on a list-file (of servers to check), it sends emails and SMS (optionnally) when encountering
an error. Every morning (or at the start time), it sends a message "I'm alive"...
