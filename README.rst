This repository contains ansible roles for setting up HDP cluster

Coverage of this ansible role repository is to cover:

* setting up java in all nodes
* setting up SSH key in all nodes
* setting up ambari in a single ambari node
* setting up repository mirror

===================
Available Roles
===================

abyres.hdpnode
================

Purpose: Setup the basic requirements on a server before it can be used as a
HDP node. 

Tasks:

* disable selinux
* install hdp repository
* install oracle java 1.7
* setup oracle java as default system java
* install SSH key
