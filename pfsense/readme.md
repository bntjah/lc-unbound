Using this to get all DNS entries into txt files so that they can be loaded into pfsense aliases.
And updated automaticly when the DNS entries change

Reason for this so I can keep my rules pretty strict and just define any 80, 443 ports on these ipv4 to go to a higher queue if it comes from my lancache alias.
If not its get thrown even lower then web traffic as this probably somebody who circumvented the DNS block :-)

Currently WIP
