## Get good at Networking

1. To connect two computers/ host in the same network you will need to use Switch.
2. To connect more computers/ host between different network you will need to use Router.
3. You need to add route to each machine via the router. A router will have gateway to connect between two/more machine.
4. By default Linux does not forward the packets from one interface to the other.
    a. You need to enable this by changing the settings in /proc/sys/net/ipv4/ip_forward.
    b. By default the value is going to be 0. If you change it to 1 then it will forward the packets.

