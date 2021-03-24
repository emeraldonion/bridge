# bridges (alpha!)

Emerald Onion hosts a 10 GbE Tor bridge in the Seattle Westin datacenter, with peering to the Seattle Internet Exchange.

The bridge shares the same 23.129.64.0/24 subnet as Emerald Onion's exit relays, so there is no risk of a user entering and exiting our physical network. The bridge runs on a dedicated 10 GbE Mac Mini running Ubuntu Server 20.10. It was configured using Tor Project's [official bridge documentation](https://community.torproject.org/relay/setup/bridge/debian-ubuntu/).

Per the [legal FAQ](https://emeraldonion.org/faq/), Emerald Onion does not log network information.

### Current node:

See its Metrics page [here](https://metrics.torproject.org/rs.html#details/09E23FA5AD9CF64DBEFE88A39A2F1EB215E44B53).

### Connect

obfs4 [2620:18c:0:192::194]:443 09E23FA5AD9CF64DBEFE88A39A2F1EB215E44B53

obfs4 23.129.64.194:443 09E23FA5AD9CF64DBEFE88A39A2F1EB215E44B53

### Donate

Emerald Onion is a 100% volunteer-run nonprofit, and 100% of donations go to business administration and insurrance, hardware, bandwidth, and co-location. Please consider becoming a monthly donor using [Github Sponsors](https://github.com/sponsors/emeraldonion)! Emerald Onion is a U.S. 501(c)(3) nonprofit, tax ID #82-2009438. Contributions are tax deductible as allowed by law.
