MIFO-userspace-tool
===================

The ip command is used in Linux to configure the ip route. 

We modify the source files of ip command, which is iproute, to enable users can further configure MIFO.

An example of configure MIFO is:

ip route add 10.0.0.0/24 deflect nexthop via 20.0.0.1 nexthop via 30.0.0.1
