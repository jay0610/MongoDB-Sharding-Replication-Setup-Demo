# MongoDB-Sharding-Replication-Setup-Demo
MongoDB Sharding &amp; Replication Setup Demo

This repository contains all the files with required configurations to build a sharded cluster with 2 replica sets each contaning 3 nodes. 

Set up consists of 9 nodes as follows: 

# Shard ReplicaSet 1
192.168.1.11	mongodb-11.local	mongodb-11
192.168.1.12	mongodb-11.local	mongodb-12
192.168.1.13	mongodb-13.local	mongodb-13

# Shard ReplicaSet 1
192.168.1.21	mongodb-21.local	mongodb-21
192.168.1.22	mongodb-22.local	mongodb-22
192.168.1.23	mongodb-23.local	mongodb-23

# Config Server ReplicaSet
192.168.1.31	config1-mongodb.local	config1-mongodb
192.168.1.32	config2-mongodb.local	config2-mongodb

# Router
192.168.1.41	router-mongodb.local	router-mongodb



Thanks.
Jay
