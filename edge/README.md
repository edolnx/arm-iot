# Edge Level Code

## Purpose

The Edge nodes will be geographically distributed to allow faster access from the sensors nodes. The edge nodes will run an MQTT broker, and then push all the appropriate data to the cloud node for permanant storage. The edge nodes can be anything, but we're using 96Boards systems running debian.

## TODO:

 - Write ansible to configure Mosquitto
 - Enable TLS on Mosquitto
 - Write code to subscribe to MQTT channels and push to Cloud data store
 - Write ansible to deploy above code
 - Deploy edge node to UK
 - Deploy edge node to IN

# DONE:

 - Deploy edge node for Southwest US in MiniNodes w/ DNS (edge-us-sw-1.iot.unfinishedcode.net)