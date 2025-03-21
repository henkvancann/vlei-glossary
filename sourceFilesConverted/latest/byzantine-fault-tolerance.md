## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/byzantine-fault-tolerance'>here</a>

## More

The term takes its name from an allegory, the "Byzantine Generals Problem", developed to describe a situation in which, in order to avoid catastrophic failure of the system, the system's actors must agree on a concerted strategy, but some of these actors are unreliable.
In a Byzantine fault, a component such as a server can inconsistently appear as both failed and functioning to failure-detection systems, presenting different symptoms to different observers. It is difficult for the other components to declare it failed and shut it out of the network because they need first to reach a consensus regarding which component has failed in the first place.
Byzantine fault tolerance (BFT) is the dependability of a fault-tolerant computer system to such conditions.

A system has Byzantine Fault Tolerance (BFT) when it can keep functioning correctly as long as two-thirds of the network agrees or reaches a consensus. BFT is a property or characteristic of a system that can resist up to one-third of the nodes failing or acting maliciously.

The pBFT model primarily focuses on providing a practical Byzantine state machine replication that tolerates Byzantine faults (malicious nodes) through an assumption that there are independent node failures and manipulated messages propagated by specific, independent nodes.
The algorithm is designed to work in asynchronous systems and is optimized to be high-performance with an impressive overhead runtime and only a slight increase in latency. More on Wikipedia about

- [Byzantine Fault](https://en.wikipedia.org/wiki/Byzantine_fault)
- [pBFT](https://en.bitcoinwiki.org/wiki/PBFT) : An article that explains practical BFT. 
- [Here](https://blockonomi.com/practical-byzantine-fault-tolerance/)'s a complete beginners guide.