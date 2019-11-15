# teradata-to-redshift-migration-using-AWS-SCT
This document contains an overview of setting Teradata(locally), Redshift(on AWS) and utilizing AWS SCT tool for schema and data migration.

# Prerequisites
Understanding of Teradata, Redshift, AWS SCT, VPC, and Networking.

# Requirements
## System Requirements:
* Minimum 12gb of local windows system RAM. Recommended is 16gb RAM
* A free IP address in the same CIDR range as of local windows system
* Attach this IP address to the static public IP address of the local windows system

# Assumptions
The Redshift cluster is publically available over port 5439 for AWS SCT to connect.

# Note
This document contains setting up Teradata on VMware workstation player 15(Linux System) and accessing the same on the local windows system. Then using a static public IP address for exposing the local Teradata over the internet. The steps/links mentioned in this document were used for carrying out a POC. 

