Basic scripts for use with more than one WAN interface

In this case we are using two WAN interfaces:
- ether1 will be WAN1
- ether2 will be WAN2

# FILE: firewall.rules

Firewall rules to create filter and mangle rules. Those rules are with comments and will be used later on another scripts to read and make use of them

# FILE: add-routes-script

Script for ease creation of /ip route rules

This script can be send to the Mikrotik router or can be copy&paste to run once.
