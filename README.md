# BGP_Router_Reflector

# Multi-As BGP Route Reflector

## Overview
This project demonstrates a Multi-AS BGP topology using iBGP with Route Reflector and eBGP peering between two autonomous system.

## Design 
- AS 500: Router 1, Router 2 (Route-Reflector), Router 3
- AS 600: Router 4
- The BGP is enabled on the loopback of all the routers to avoid single point of failure. (Redundancy)
- OSPF is used for loopback reachability between the routers
- iBGP session is formed using loopback interfaces
- eBGP session between AS 500 and AS 600

## Technologies 
-Cisco IOS
-BGP (IBGP, EBGP and Route Reflector)
-OSPF
