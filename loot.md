# Loot and Enumerate

After you have gained access to a machine you must loot it. This is useful in order to be able to pivot into other machine.  

If you are on a network with other machines that you still haven't owned, it might be useful to take a tcp-dump from the machine you have owned. So that you can inspect the traffic between that machine and the other machines on the network. This might be helpful when attacking the other machines.

So after we have exploited a machine we want to use that machine to learn as much about the network as possible. To be able to map the entire network. We want to know about switches, firewalls, routers, other computers, server, etc. We want to know what ports are open, their operating systems.

We can start getting an understanding of the network by taking a tcp-dump.

We also want to look for password that might be reused on other machines, and sensitive information found in databases. Information about the user might be interesting in order to use social engineering attacks against other users in the network.

