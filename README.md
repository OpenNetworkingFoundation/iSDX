# iSDX
iSDX: An Industrial-Scale Software-Defined IXP

This project, donated by individuals who currently are affiliated with Princeton University (which declaims all interest, rights, or license thereunto), is presently hosted on an independent GitHub repository. The repository is located at https://github.com/sdn-ixp/iSDX/

iSDX (Software-Defined IXP) Software brings the merits of SDN to interdomain routing. Today’s networks can only forward traffic based on the destination IP prefixes and routes offered by their immediate neighbors. SDN can give direct control over packet-processing rules that match on multiple header fields and perform a variety of actions. 

IXPs are a compelling place to deploy these changes, given their role in interconnecting many networks and their growing importance in bringing popular content closer to end users.

SDX does more than simply replace an IXP’s switches with their OpenFlow counterparts. SDX's capabilities enable new applications, such as application-specific peering---where two networks peer only for (say) streaming video traffic. We also developed new programming abstractions that allow participating networks to create and run these applications and a runtime that both behaves correctly when interacting with BGP and ensures that applications do not interfere with each other. Finally, we also ensured that the system scales, both in terms of table size and computational overhead.

We are involved in several trial deployments of the SDX controller at various IXPs around the world, in collaboration with network operators.

The license for the project is OSSDN Apache 2.0, and all documents will be licenced Creative Commons CC4.0 BY.

More information about the project is located on the website, http://sdx.cs.princeton.edu/


