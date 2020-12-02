# Assignment-Code
Created 3 subnets in different regions of a new Custom VPC.

Created 3 VM instances in 3 different subnets of the VPC.

Only Bastion host has a public IP address so that we can connect to it.

app and web instance has private IP only.

Created Firewall rule to allow ssh connection to bastion host from a specific IP.

Created private and public key with ssh-keygen command.

Pasted the content of Public key in Metadata Server, so that we can connect to the Bastion host VM with a specific username.

Created Firewall rule to allow bastion host VM to connect to app and web instance on port 22.

Installed httpd and curl softwares in the app and web instances.

Created Firewall rule to be able to connect to port 443 of web instance.

Created Firewall rule to be able to connect to app instance from web instance on port 80 and vice versa.

Created a firewall rule to block the connection of app instance to web instance on port 443.
