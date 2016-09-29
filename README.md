# ixiaconfigs
IxNetwork configurations

### basic_ebgp.ixncfg
Single port configuration showing basic external BGP CPE connection.
### basic_ibgp.ixncfg
Single port configuration using the loopback method in Device Group without an IGP present.  DUT would reply on a static route to reach this CPE.
### basic_ibgp_ospg.ixncfg
Single port configuration using loopback but 2nd device group along with OSPF as IGP for loopback reachability.
### basic_ebgp_ospf_mix.ixncfg
This configuration was an attempt to test diversifing BGP and OSPF routes.  Advertising a number of BGP routes as well as OSPF (not just loopback).  Not sure if this is fully working.
### basic_l3vpn.ixncfg
This configuration includes 2 ports, one using ebgp for CPE side and another simulating the MPLS core using LDP with two remote PEs.  This config could be built up on either side (# of P routers, PE routers, CPE, etc)

