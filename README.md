#### README.md

##### Ansible Based Automated Configuration System:
The Ansible playbooks (scripts) contained in this repository are a small set representing a larger server configuration system. They are intended to give an idea of a few of the capabilities possessed and technologies understood by the developer of the scripts.

##### Technologies Represented
Ansible, Nginx, Redis, MySQL cluster, Tinc.

##### Description of Playbooks:
- <b>full_cluster_build.yml</b>: Top level script for building a full cluster.

- <b>nginx_setup.yml</b>: Script for installing, and configuring Nginx on a cluster of servers with identical builds.

- <b>redis_setup.yml</b>: Script for installing and configuring Redis, and Redis PHP for persistent, highly available sessions in PHP.

- <b>setup_tinc.yml</b>: Script for installing Tinc, a peer to peer VPN client for secure communication among cluster nodes on an untrusted network.

- <b>setup_mysql_clustering.yml</b>: Script for installing galera and  building a MySQL cluster for data redundancy and high availability.
