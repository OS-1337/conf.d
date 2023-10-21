# OS/1337
### Default Configurations

---
## Server List
### NTP Servers
#### Sourced from: [lists.d](https://github.com/greyhat-academy/lists.d/blob/main/ntp.servers.list.tsv)
````
ptbtime1.ptb.de
ntp.nict.jp
time.nist.gov
ntp.ripe.net
time.esa.int 
````
- These are all either
  - goverment agencies or 
  - intergovermental agencies or
  - international authorities that have to provide accurate time.
###

### DNS Servers
#### Sourced from: [lists.d](https://github.com/greyhat-academy/lists.d/blob/main/dns.servers.list.tsv)
````
94.103.153.176
144.76.103.143
2a02:990:219:1:ba:1337:cafe:3
2a01:4f8:192:43a5::2
````
- Both are [OpenNIC Tier 1 Public Servers](https://servers.opennic.org/) and this extend the namespace beyond the ICANN-Rootzone.
##### NOTE: The "CORE" Version of OS/1337 does not come with IPv6 support!!!
###

### Other Entries in [default.conf.ydl](../configs/default.conf.ydl)
#### WireGuard
This is a [sample configuration from netplan.io](https://netplan.readthedocs.io/en/stable/examples/#how-to-connect-two-systems-with-a-wireguard-vpn)
#### Dialup Modem
##### Sourced from: [lists.d](https://github.com/greyhat-academy/lists.d/blob/main/dialup.providers.list.tsv)
This is based upon [Iridium Direct Internet](https://github.com/greyhat-academy/lists.d/blob/4b76b3de6849e8961e9c399d80cc4e0ea5e87ad0/dialup.providers.list.tsv#L2) as connection to showcase setup of the necessary parameters.
