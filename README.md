# dhcp-relay

Alpine DHCP Relay

## quick start (no daemon, forward dhcp requests to server)

````
$> docker run \
--rm \
-ti \
-p 67:67 \
-p 67:67/udp \
--cap-add NET_ADMIN \
shokohsc/dhcp-relay
-s 192.168.0.42
````
## help

````
$> docker run \
--rm \
-ti \
--cap-add NET_ADMIN \
shokohsc/dhcp-relay
--help
````
