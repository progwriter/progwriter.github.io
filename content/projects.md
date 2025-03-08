
## Evolving AWS Networking control plane

I have worked on various parts of the AWS intent-driven network control plane, from building the intent infrastructure to working on a new routing protocol. More info available in this [re:Invent presentation](aidnsidr)

## Batfish

I continue contributing to [Batfish](bf), an open source tool for network configuration analysis. Batfish has broad use in the networking community, and has been adopted at AWS as well. I was the core developer for the routing simulation engine. These days mostly focused on closing vendor gaps and supporting users. 

### Past projects

#### Network Access Control  

At AWS, I built a service for verifying network access control lists (ACLs) using formal methods.

#### AWS Reachability Analyzer

While at AWS, I briefly worked on a service that powered [AWS reachability analyzer](ra).

#### SDN Optimization Layer (SOL)

During my PhD at [UNC][unccs], I explored the intersection of Software-Defined Networking (SDN) and global network optimization.
In particular, I looked at how to efficiently write and execute SDN applications that try to perform optimal resource
management (e.g., traffic engineering) in the SDN world.
As a result, I ended up developing a library called SOL for expression and composition SDN resource-management applications.

#### [Gremlin][gremlin-research] --- microservice resilience testing

On an internship at [IBM Research][ibm-research], I helped start a project for resiliency testing of
microservice applications. We
built an automated testing framework for stress-testing microservice applications and checking if they are resistant to failures.

[aidnsidr]: https://aws.amazon.com/id/awstv/watch/1a691d9dc18/
[ra]: https://docs.aws.amazon.com/vpc/latest/reachability/what-is-reachability-analyzer.html
[bf]: https://github.com/batfish/batfish
[bfpaper]: https://dl.acm.org/doi/abs/10.1145/3603269.3604866

[unc]: https://unc.edu/
[unccs]: https://cs.unc.edu/
[mike]: https://cs.unc.edu/~reiter
[vyas]: https://users.ece.cmu.edu/~vsekar

[sol]: https://github.com/progwriter/SOL

[gremlin-research]: https://github.com/ResilienceTesting
[ibm-research]: https://www.research.ibm.com/labs/watson/
