# Openbsd-NAT-firewall
PF firewall, Unbound DNS filter

I want to control what kind of usage, user at LAN get acess to. 
I dont want them getting me into trouble with virus, spamming or legal by access content not legal.
Normal usage of streming, clouds, media sites, gaming should work fine.

Goals:
DNS : https://cleanbrowsing.org/ filter, added to unbound dns server
Blocklist-DE added to PF firewall, updated by cron job
Trafic shaping whitelist topp 100 000 legit sites 
Trafic shaping blacklist manualy or by scrip run by cron
Add Suricata and get it to speak with PF firewall

