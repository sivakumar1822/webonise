# webonise

Scenario: 
Client X’s software system exists on their company’s own hardware, and they no longer want the maintenance costs.
They plan on moving from private servers to Amazon Web Servers (AWS) and have asked you for assistance.

Original Data Center:
- 1 haproxy load balancer pointing to the 2 web servers.
- 2 web app servers running nginx + php-fpm
- 2 mysql databases, 1 master, 1 slave 
- Systems are all running Ubuntu 14.04

Perform the following tasks:
- Terraform Script to launch this infra in AWS
- Puppet or Ansible to configure VM 
- Write MySQL Backup Script 
