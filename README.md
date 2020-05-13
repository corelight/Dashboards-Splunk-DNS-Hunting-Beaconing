# DNS Hunting-Beaconing

DNS Dashboard for hunting and identifing beaconing 

This dashboard uses a Splunk lookup table to identify "Trusted Domains".  It also requires a Corelight/Zeek script to parse the DNS query into the required components.

An example of the lookup talble is in this repository, edit as necessary.

The script can be found here, https://maestro.corelight.io/dns/icanntld