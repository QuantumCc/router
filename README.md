Approach:

I started with the skeleton, followed the order described in the project. The dispatch methods handle_packet is basically a function that determines which certain function to perform based on the packet type. 

> To forward/update the packet, it's necessary to first distinguish who you receive the packet from, and then determine who to forward to.
> To dump the packet, basically the router dump what it has in its forwarding table after receiving a 
dump message.
> To revoke a packet, the router has to clear its forwarding table and then call coalesce on every entry .


Challenges:
> No awareness of adding asn to the field which leads to a tough start.
> Not familiar with Python
> Spent tons of time stackoverflowing while trying to converts addresses from decimal to binary format and vice versa.


