# Cloud Level Code

## Purpose

The cloud node becomes the end of the road and central data store for the entire system. It can run on anything in the cloud, but we choose a Ampere based server at Packet's EWR facility. This is also where the visulization of the data will be done, and the public front end for the project.

## TODO:

 - Pick a data store and visulizer (InfluxDB+Grafana or ELK)
 - Ansible to deploy and configure data store and visualizer
 - Let's Encrypt cert for web server

## DONE:

 - Provision server
 - Assign DNS name (iot.unfinishedcode.net)

