# Why should we talk about networking?

#### [prev](./readme.md) | [home](./readme.md)  | [next](./concepts.md)

## Networking in Azure is defined virtually (what is this "Fabric" I keep hearing about)

This means networking concepts learnt traditionally don't always apply.

This also means newer techniques are available when designing a network topology.

## Common traps and wrong assumptions

Thinking there is still layer 2
- Running a DHCP server in Azure.
- Multiple NICs on NVAs.

Force tunneling and hair-pinning
- Assuming no public IP equals no internet access.
- Fear of Public Endpoints.

VNet mistakes
- Nesting VNets.
- Forgetting to use NSGs.
- Asking too much from NSGs.
- Trying to put PaaS services "into" a VNet when there is no requirement to do so.

Security mistakes
- Low segmentation/high trust design.
- Not leveraging Identity as the primary security layer.
- Not considering logging requirements in network design.


Troubleshoot difficulties
- Using ICMP.
- The platform does routing not the VMs.
- Misconfigured DNS.

