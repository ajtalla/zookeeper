# Apache ZooKeeper

Ansible role for installing and configuring Apache ZooKeeper on RHEL / CentOS 7.

This role can be used to install and cluster multiple ZooKeeper nodes, this uses all hosts defined for the "zookeeper-nodes" group
in the inventory file by default. All servers are added to the zoo.cfg file along with the leader and election ports.

## Requirements

Platform: RHEL / CentOS 7

Java: Java 8
