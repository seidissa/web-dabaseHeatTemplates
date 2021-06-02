# web-dabaseHeatTemplates
The objective of the program is to Construct a Heat template file that installs, configures and launches a Wordpress running on two VM instances: a wordpress with web server and a database server with the following network setups.
An internal/private network and subnetwork, which is connected to the web and database servers.
In the internal/private network set the DNS server(e.g. Public Google DNS 8.8.8.8).
A virtual router that is connected to this internal/private network.
The virtual router is then connected to the external network.
A floating IP is assigned to the web server VM.
In the security group settings the incoming web, ssh and ping connections are enabled for the servers.

