# SEcure Networks and Devices Laboratory


We are an [academic research group](people.md) at the [Rochester Institute of Technology](https://rit-sendlabs.github.io/).

Our focus is on Network and Internet Security.

## Network Security? That's a Broad Area!

True! There are various perspectives we can use to understand networks.
- Networks themselves: the graph of connections
- How specific devices function (switches, routers, middleboxes)
- Questions of consensus, e.g. for routing tables

And network _security_ is particularly interesting, because it requires us to look at each of these in detail. 
We can't just assume things work right; it's necessary to dig deep and check. 

## What specific problems are you interested in?

We are looking into the power of "smart switches". 

In particular, with the rise of SDN, we can see how more and more powerful programming models are available on network infrastructure.

What is possible at each level of power?
- simple OpenFlow? 
- OpenState?
- P4-compatible e.g. PISA switches?
- nVidia Data Processing Unit (DPU)?

For example, our big recent project [SiegeBreaker](https://petsymposium.org/2020/files/papers/issue3/popets-2020-0051.pdf) (in PETS 2020) 
explored how to build true Decoy Routers using standard (OpenFlow) SDN.

Our current big project is, to challenge the conventional wisdom that "P4 cannot do DPI". 
Building on recent work from Nate Foster, we believe that it is possible to perform simple Deep-Packet-Inspection tasks.

## That's the "devices" part. What about networks?

We are interested in complex algorithms, for network-related tasks, that can be implemented on these devices. 
- multi-pathing algorithms for fault-tolerance.
- building middleboxes, URL inspection etc.
- in future, we will look into Network IDS functions.

We are also interested in the possibility of very large-scale deployments. For example, Rexford has suggested SDN-based ISP and IXP. 
What might be the motivation for such large-scale retooling of the Internet? - CDNs? Content Filtering? Possibly even transition to 
a next-generation Internet architecture (such as XIA)? - these are long term questions we aspire to look at.
