# bridges (alpha!)

Emerald Onion hosts a 10 GbE Tor bridge in the Seattle Westin datacenter, with peering to the Seattle Internet Exchange.

The bridge shares the same 23.129.64.0/24 subnet as Emerald Onion's exit relays, so there is no risk of a user entering and exiting our physical network. The bridge runs on a dedicated 10 GbE Mac Mini running Ubuntu Server 20.10. It was configured using Tor Project's [official bridge documentation](https://community.torproject.org/relay/setup/bridge/debian-ubuntu/).

Per the [legal FAQ](https://emeraldonion.org/faq/), Emerald Onion does not log network information.

### Current node:

See its Metrics page [here](https://metrics.torproject.org/rs.html#details/7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3).

### Connect

obfs4 [2620:18c:0:192::194]:443 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3

obfs4 23.129.64.194:443 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3
