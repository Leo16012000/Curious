Hazelcast cluster with **single** member:

![[Pasted image 20240229172734.png]]

2 member
![[Pasted image 20240229172756.png]]
As you **add more** members, Hazelcast **moves** some of the primary and backup partition replicas to the new members **one by one**, making all members **equal** and **redundant**.
![[Pasted image 20240229172817.png]]
Repartitioning is the process of redistribution of partition ownerships. Hazelcast performs the repartitioning when **a member joins or leaves the cluster.**