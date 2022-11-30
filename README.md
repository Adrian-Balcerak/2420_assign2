# ACIT 2420 Assignment 2

## Author
**Adrian Balcerak**

## Step 1
Follow along with the video to create:
* a VPC: 10.124.16.0/20
* two droplets: 164.92.124.144, and 137.184.11.22
* a load balancer: 143.244.208.55
* a firewall that: accepts inbound SSH traffic from all IPV4 and IPV6 addresses and inbound HTTP traffic from the load-balancer 143.244.208.55

## Step 2
Create regular users on both droplets:

### Create Regular User 1
* ssh -i ~/.ssh/DO_key root@164.92.124.144
* useradd -ms /bin/bash johnny
* usermod -aG sudo johnny
* passwd johnny
* (set password as johnny)

### Create Regular User 2
* ssh -i ~/.ssh/DO_key root@137.184.11.22
* useradd -ms /bin/bash johnny
* usermod -aG sudo johnny
* passwd johnny
* (set password as johnny)

## Step 3
