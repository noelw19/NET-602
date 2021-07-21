# Learning Active Directory

### What is Active Directory?

1. It is a microsoft Technology
2. Provides Centralised Network Management
3. Easily Scalable
4. Is used to power many enterprise networks

##### Peer to Peer Network
each device has its own local security database that holds passwords etc

users have to add a user account to the specific pc the user is on, and when wanting to share data the users account needs to be added to the pc that you wish to share data with.

Suggested limit for peer to peer is 10-15 users

##### Client/Server Network
Directory Service saves crendentials on a central device, where the admin can make changes in a central area rather than in multiple areas on the network.

#### Active Directory
is a suite of service with ADDS at the heart of the suite.

When we add Active Directory Domain Services to a server we are creating a centrally managed on-premise microsoft windows server network.

server is then promoted to become DC

main role of the DC is to host the ADDS Database:
this stores info of network objects.
also stores important AD config info

Good practice to have more than one DC

### Replication
To replicate config on another DC and allows for availability on the network if one of the DC's fails for some reason.

ADDS - allows us to organise and structure objects.
Forest is a container of all AD Objects
Domains - contain objects such as users, computers OU's
Trees - more than 1 domain in a forest creates a tree.


