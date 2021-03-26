# bridges (alpha!)

Emerald Onion hosts a public Tor bridge in the Westin datacenter in Seattle, WA with direct peering to the [Seattle Internet Exchange](https://www.seattleix.net/).

### How to connect?

Please review Tor Project's documentation on how to use bridges [here](https://tb-manual.torproject.org/bridges/).

### Connect

IPv6 with obfs4proxy:
`obfs4 [2620:18c:0:192::194]:443 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3`

IPv4 with obfs4proxy:
`obfs4 23.129.64.194:443 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3`

IPv6 without obfs4proxy:
`[2620:18c:0:192::194]:80 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3`

IPv4 without obfs4proxy:
`23.129.64.194:80 7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3`

### Technical

The bridge shares the same 23.129.64.0/24 subnet as Emerald Onion's [Tor exit relays](https://metrics.torproject.org/rs.html#search/as:396507), so there is no risk of a user entering and exiting our physical network (see "[2.2. Path selection and constraints](https://github.com/torproject/torspec/blob/master/path-spec.txt)"). The bridge runs on a dedicated Apple Mac Mini with [10Gb Ethernet](https://support.apple.com/kb/SP782?locale=en_US) running Ubuntu Server. It was configured using Tor Project's [official bridge documentation](https://community.torproject.org/relay/setup/bridge/debian-ubuntu/).

### Legal

Per the [legal FAQ](https://emeraldonion.org/faq/), Emerald Onion does not log network information. To report abuse, please contact [Abuse](mailto:abuse@emeraldonion.org).

### Donate

Emerald Onion is 100% volunteer-run, and 100% of donations go to business administration and insurrance, hardware, bandwidth, and co-location. Please consider becoming a monthly donor using [Github Sponsors](https://github.com/sponsors/emeraldonion)!

Other donation methods are available here: [emeraldonion.org/donate](https://emeraldonion.org/donate/)

The Apple Mac Mini discussed here was purchased by Emerald Onion via a direct donation made for the explicit purpose of running bridges, to enhance the Tor network with greater hardware diversity. This wouldn't have been possible without our donors. Thank you!

Emerald Onion is a U.S. 501(c)(3) nonprofit, tax ID #82-2009438. Contributions are tax deductible as allowed by law.

### Metrics

See Tor Project's Metrics page for the Tor bridge [here](https://metrics.torproject.org/rs.html#details/7ADC8C6BF93197830FDF3E06DFB4D96E7CFEDCF3).
